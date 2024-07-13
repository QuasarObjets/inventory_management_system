# tRPC

Esta carpeta contiene los archivos relacionados con tRPC, una biblioteca que se utiliza para definir los controladores y rutas de la API en el proyecto de gestión de inventarios.

## Archivos

- `controlador1.ts`: Este archivo contiene el controlador 1 de la API. Define las funciones y rutas correspondientes a las operaciones relacionadas con el inventario.

- `controlador2.ts`: Este archivo contiene el controlador 2 de la API. Define las funciones y rutas correspondientes a las operaciones relacionadas con la gestión de usuarios.

## Uso

Para utilizar los controladores y rutas definidos en tRPC, sigue estos pasos:

1. Asegúrate de tener todas las dependencias instaladas ejecutando `npm install` en la raíz del proyecto.

2. Importa los controladores necesarios en el archivo principal de la API.

```typescript
import { createRouter } from 'trpc';
import { controlador1 } from './controlador1';
import { controlador2 } from './controlador2';

const router = createRouter()
  .merge('controlador1', controlador1)
  .merge('controlador2', controlador2);

export default router;
```

3. Configura las rutas en el archivo de configuración de la API.

```typescript
import { createNextApiHandler } from 'trpc/server/adapters/next';
import { router } from './router';

export default createNextApiHandler({
  router,
});
```

4. Inicia el servidor de desarrollo ejecutando `npm run dev` en la raíz del proyecto.

5. Accede a las rutas definidas en los controladores a través de la URL base de la API.

```plaintext
GET /api/controlador1/obtener-inventario
POST /api/controlador1/agregar-item
PUT /api/controlador1/actualizar-item
DELETE /api/controlador1/eliminar-item

GET /api/controlador2/obtener-usuarios
POST /api/controlador2/agregar-usuario
PUT /api/controlador2/actualizar-usuario
DELETE /api/controlador2/eliminar-usuario
```

Recuerda que estas rutas son solo ejemplos y debes ajustarlas según las necesidades de tu proyecto.

Para obtener más información sobre cómo utilizar tRPC, consulta la documentación oficial en [enlace a la documentación de tRPC](https://trpc.io/docs/).

Este archivo es solo una guía básica para comenzar a utilizar tRPC en el proyecto de gestión de inventarios. Asegúrate de leer la documentación oficial y ajustar el código según tus necesidades específicas.

¡Feliz desarrollo!