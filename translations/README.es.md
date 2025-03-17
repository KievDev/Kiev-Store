<h1 align="center"><a href="https://kiev-store.onrender.com">KIEVSTORE</a></h1>

![Demo App](/frontend/public/demo-app.png)
<br/>
<h1>El Proyecto</h1>
<p>El principal motivo del proyecto era demostrar el uso de diversas tecnologías modernas en una aplicación de pila completa, con especial atención a la pila PERN.

En total, hay 13 temas para que el usuario elija y personalice su experiencia a voluntad.

Podemos añadir un producto a la base de datos, junto con su nombre, precio y foto, editar cada una de estas cosas y eliminar los mismos productos también.

Disponemos de una función de «refresco», para poder obtener los datos más recientes de la base de datos.

Códigos y carpetas limpiamente estructurados, para que sea fácil de mantener y escalable.</p>
<br/>
![Product Demo](/frontend/public/demo-product.png)
<br/>
<h1>Temas</h1>
<p>Como ya se ha mencionado, hay 13 temas diferentes entre los que elegir.

Aquí tienes algunos ejemplos además del ya mostrado.</p>
<div align="center" display="flex" flex-direction="row" justify-content="center">
  
![Theme Demo 1](/frontend/public/theme1.png)![Theme Demo 2](/frontend/public/theme2.png)
</div>
<br/>
<h1>Tech Stack</h1>
<ul>
  <br/>
  <li>Frontend</li>
    <ul>
      <br/>
      <li>React.js – El núcleo de la biblioteca frontend que construye interfaces de usuario interactivas con componentes reutilizables. Ayuda a gestionar los datos dinámicos y el estado de forma eficiente.</li>
      <li>Tailwind CSS – Un framework CSS que acelera la creación de estilos sin necesidad de escribir CSS personalizado. Ideal para diseños adaptables.</li>
      <li>DaisyUI – Una biblioteca de componentes de interfaz de usuario basada en Tailwind que proporciona componentes preestilizados, reduciendo el tiempo de desarrollo.</li>
      <li>Lucide Icons – Un conjunto de iconos limpio y personalizable para mejorar el diseño de la interfaz de usuario. Útil para botones, navegación y alertas.</li>
      <li>Hot Toast – Una biblioteca ligera de notificaciones tostadas para mostrar alertas, errores y mensajes de éxito en tu aplicación.</li>
      <li>Zustand – Una librería de gestión de estados para React que es más simple y ligera que Redux. Útil para la gestión global de estados.</li>
      <li>Vite – Una rápida herramienta de creación de frontales y servidor de desarrollo que sustituye a Webpack para mejorar el rendimiento y acelerar la recarga en caliente de módulos (HMR).</li>
      <br/>
    </ul>
  <li>Backend</li>
    <ul>
      <br/>
      <li>Node.js – El tiempo de ejecución que permite que JavaScript se ejecute en el lado del servidor, gestionando la lógica de backend y las solicitudes de API.</li>
      <li>Express.js – Un framework ligero de Node.js para construir APIs. Gestiona rutas, middleware y lógica de servidor de forma limpia.</li>
      <li>PostgreSQL – Una potente base de datos relacional utilizada para almacenar datos estructurados para su aplicación, a la que se accede mediante consultas SQL.</li>
      <br/>
    </ul>
  <li>Tools & Cloud</li>
    <ul>
      <br/>
      <li>Neon Tech – Un servicio PostgreSQL sin servidor nativo en la nube. Proporciona una solución de base de datos gestionada con autoescalado, lo que facilita el despliegue.</li>
      <li>Arcjet – Un servicio de despliegue y alojamiento, probablemente utilizado para desplegar su backend y base de datos con una configuración mínima.</li>
      <li>Postman – Una herramienta de pruebas de API que le ayuda a enviar solicitudes a su backend, depurar API y probar puntos finales fácilmente.</li>
      <br/>
    </ul>
</ul>

### Configurar archivo .env

```js
PORT=3000

PGUSER=...
PGPASSWORD=...
PGHOST=...
PGDATABASE=...

ARCJET_KEY=...
ARCJET_ENV=development
```

### Ejecutar la API

```shell
npm run dev
```

### Ejecutar el frontend

```shell
cd frontend
npm run dev
```
<br/>
<p>...y por último, pero no por ello menos importante, ¡responde al 100%!</p>
