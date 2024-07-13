# Prisma

Este proyecto utiliza Prisma como ORM (Object-Relational Mapping) para gestionar la base de datos PostgreSQL. Prisma permite definir el esquema de la base de datos y generar automáticamente el código necesario para interactuar con ella.

## Configuración

1. Asegúrate de tener PostgreSQL instalado y en funcionamiento en tu máquina.

2. Abre el archivo `api/prisma/schema.prisma` y define las tablas y relaciones necesarias para tu aplicación. Puedes consultar la documentación de Prisma para obtener más información sobre cómo definir el esquema.

3. Ejecuta el siguiente comando para generar el código de Prisma:

   ```bash
   npx prisma generate
   ```

   Esto generará el código necesario para interactuar con la base de datos según el esquema definido en `schema.prisma`.

4. Configura la conexión a la base de datos en el archivo `api/prisma/schema.prisma`. Asegúrate de proporcionar la URL de conexión correcta para tu base de datos PostgreSQL.

## Uso

Una vez configurado Prisma, puedes utilizar los modelos generados para realizar operaciones de lectura, escritura y actualización en la base de datos.

Por ejemplo, para obtener todos los elementos de una tabla llamada "Inventario", puedes utilizar el siguiente código en un controlador de tRPC:

```typescript
import { prisma } from '../prisma/client';

export const getInventario = async () => {
  const inventario = await prisma.inventario.findMany();
  return inventario;
};
```

Este código utiliza el modelo `inventario` generado por Prisma para realizar una consulta a la base de datos y devolver todos los elementos de la tabla "Inventario".

Puedes consultar la documentación de Prisma para obtener más información sobre cómo utilizar los modelos generados y realizar diferentes operaciones en la base de datos.

```

Recuerda que este archivo es solo una plantilla y debes personalizarlo según las necesidades específicas de tu proyecto.