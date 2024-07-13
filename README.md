# StockMaster - Gestión de Inventarios - Aplicación Web y Móvil

Este proyecto tiene como objetivo crear un sistema para rastrear y gestionar inventarios en tiempo real. Utiliza la siguiente tecnología:

- Next.js: Framework de React para la construcción de aplicaciones web.
- TypeScript: Lenguaje de programación tipado utilizado en el proyecto.
- Tailwind CSS: Framework de CSS utilizado para estilizar la interfaz de usuario.
- tRPC: Biblioteca utilizada para la comunicación entre el cliente y el servidor.
- Prisma: ORM utilizado para la conexión y manipulación de la base de datos PostgreSQL.
- NextAuth.js: Biblioteca utilizada para la autenticación y autorización en la API.
- PostgreSQL: Sistema de gestión de bases de datos utilizado en el proyecto.

## Estructura de archivos

- `api/prisma/schema.prisma`: Este archivo es el esquema de base de datos de Prisma. Define la estructura de las tablas y relaciones en la base de datos PostgreSQL.

- `api/prisma/README.md`: Este archivo contiene información adicional sobre el uso de Prisma y cómo configurar la conexión con la base de datos.

- `api/trpc`: Esta carpeta contiene varios archivos `.ts` relacionados con tRPC. Estos archivos definen los controladores y rutas de la API utilizando tRPC para la comunicación entre el cliente y el servidor.

- `api/trpc/README.md`: Este archivo contiene información adicional sobre el uso de tRPC y cómo configurar los controladores y rutas de la API.

- `api/next-auth`: Esta carpeta contiene archivos de configuración para NextAuth.js. Estos archivos definen la autenticación y autorización en la API utilizando NextAuth.js.

- `api/next-auth/README.md`: Este archivo contiene información adicional sobre el uso de NextAuth.js y cómo configurar la autenticación y autorización en la API.

- `api/README.md`: Este archivo contiene información general sobre la API y cómo utilizarla.

- `web/pages/index.tsx`: Este archivo es la página principal de la aplicación web. Contiene el código React para mostrar la interfaz de usuario y realizar solicitudes a la API.

- `web/pages/_app.tsx`: Este archivo es el componente de envoltura de la aplicación web. Se utiliza para agregar estilos globales y configurar el enrutamiento.

- `web/pages/README.md`: Este archivo contiene información adicional sobre las páginas de la aplicación web y cómo utilizarlas.

- `web/components`: Esta carpeta contiene varios componentes de React utilizados en la aplicación web. Estos componentes se utilizan para construir la interfaz de usuario.

- `web/components/README.md`: Este archivo contiene información adicional sobre los componentes de la aplicación web y cómo utilizarlos.

- `web/styles/globals.css`: Este archivo contiene estilos CSS globales que se aplican a toda la aplicación web.

- `web/styles/README.md`: Este archivo contiene información adicional sobre los estilos de la aplicación web y cómo utilizarlos.

- `web/README.md`: Este archivo contiene información general sobre la aplicación web y cómo utilizarla.

- `mobile/src/App.tsx`: Este archivo es el punto de entrada de la aplicación móvil. Contiene el código React Native para mostrar la interfaz de usuario y realizar solicitudes a la API.

- `mobile/src/components`: Esta carpeta contiene varios componentes de React Native utilizados en la aplicación móvil. Estos componentes se utilizan para construir la interfaz de usuario.

- `mobile/src/components/README.md`: Este archivo contiene información adicional sobre los componentes de la aplicación móvil y cómo utilizarlos.

- `mobile/src/README.md`: Este archivo contiene información general sobre la aplicación móvil y cómo utilizarla.

- `package.json`: Este archivo es el archivo de configuración de npm. Lista las dependencias y scripts para el proyecto.

- `tsconfig.json`: Este archivo es el archivo de configuración de TypeScript. Especifica las opciones del compilador y los archivos a incluir en la compilación.

- `README.md`: Este archivo contiene la documentación general del proyecto y las rutas de acceso a los archivos y carpetas mencionados anteriormente.
```

Recuerda que puedes agregar más información y detalles a este archivo según tus necesidades.