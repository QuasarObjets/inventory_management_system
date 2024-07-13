# API

Esta carpeta contiene la API para rastrear y gestionar inventarios en tiempo real.

## Estructura de archivos

- `prisma/schema.prisma`: Este archivo es el esquema de base de datos de Prisma. Define la estructura de las tablas y relaciones en la base de datos PostgreSQL.

- `prisma/README.md`: Este archivo contiene información adicional sobre el uso de Prisma y cómo configurar la conexión con la base de datos.

- `trpc`: Esta carpeta contiene varios archivos `.ts` relacionados con tRPC. Estos archivos definen los controladores y rutas de la API utilizando tRPC para la comunicación entre el cliente y el servidor.

- `trpc/README.md`: Este archivo contiene información adicional sobre el uso de tRPC y cómo configurar los controladores y rutas de la API.

- `next-auth`: Esta carpeta contiene archivos de configuración para NextAuth.js. Estos archivos definen la autenticación y autorización en la API utilizando NextAuth.js.

- `next-auth/README.md`: Este archivo contiene información adicional sobre el uso de NextAuth.js y cómo configurar la autenticación y autorización en la API.

## Uso

Para utilizar la API, siga los siguientes pasos:

1. Configurar la base de datos en `prisma/schema.prisma` según sus necesidades.

2. Ejecutar las migraciones de la base de datos utilizando Prisma.

3. Configurar los controladores y rutas de la API en la carpeta `trpc`.

4. Configurar la autenticación y autorización en la carpeta `next-auth`.

5. Iniciar el servidor de la API.

## Documentación adicional

Consulte los archivos `prisma/README.md`, `trpc/README.md` y `next-auth/README.md` para obtener información adicional sobre el uso de Prisma, tRPC y NextAuth.js respectivamente.

```
```