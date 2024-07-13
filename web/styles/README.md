# Estilos de la Aplicación Web

Esta carpeta contiene los estilos CSS globales que se aplican a toda la aplicación web.

## Archivos

- `globals.css`: Este archivo contiene los estilos CSS globales que se aplican a todos los elementos de la aplicación web.

## Uso

Puedes utilizar los estilos globales en tus componentes de la siguiente manera:

```jsx
import React from 'react';
import '../styles/globals.css';

const App = () => {
  return (
    <div className="container">
      <h1 className="title">Mi Aplicación Web</h1>
      <p className="description">Bienvenido a mi aplicación web.</p>
    </div>
  );
};

export default App;
```

En el ejemplo anterior, hemos importado el archivo `globals.css` y aplicado las clases CSS definidas en ese archivo a los elementos HTML en nuestro componente.

Recuerda que puedes personalizar los estilos globales según las necesidades de tu aplicación.

## Documentación Adicional

Para obtener más información sobre cómo utilizar los estilos en la aplicación web, consulta la documentación en la raíz del proyecto.

---

Este archivo es parte del proyecto de gestión de inventarios. Para obtener más información sobre la estructura del proyecto y las rutas de acceso a otros archivos y carpetas, consulta el archivo `README.md` en la raíz del proyecto.