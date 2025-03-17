<h1 align="center"><a href="https://kiev-store.onrender.com">KIEVSTORE</a></h1>
<p align='center'>You can read this in other languages:</p>
<div align="center">

<kbd>[<img title="Português (Brasil)" alt="Português (Brasil)" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/br.svg" width="22">](README.pt_br.md)</kbd>
<kbd>[<img title="Deutsch" alt="Deutsch" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/de.svg" width="22">](README.de.md)</kbd>
<kbd>[<img title="Española" alt="Española" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/es.svg" width="22">](README.es.md)</kbd>
<kbd>[<img title="Русский язык" alt="Русский язык" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/ru.svg" width="22">](README.ru.md)</kbd>
</div>
<br/>

![Demo App](/frontend/public/demo-app.png)
<br/>
<h1>The Project</h1>
<p>The main reason for the project was to demonstrate the use of various modern technologies in a full-stack application, with a focus on the PERN stack.

In all, there are 13 themes for the user to choose from and customize their experience at will.

We can add a product to the database, along with its name, price and photo, edit each of these things and delete the same products too.

We have a “refresh” function, so we can get the latest data from the database.

Cleanly structured codes and folders, to be easy to maintain and scalable.</p>
<br/>
![Product Demo](/frontend/public/demo-product.png)
<br/>
<h1>Themes</h1>
<p>As mentioned above, there are 13 different themes to choose from.
  
Here are some examples besides the one already shown.</p>
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
      <li>React.js – The core frontend library that builds interactive UIs with reusable components. It helps manage dynamic data and state efficiently.</li>
      <li>Tailwind CSS – A utility-first CSS framework that speeds up styling without writing custom CSS. Great for responsive designs.</li>
      <li>DaisyUI – A Tailwind-based UI component library that provides pre-styled components, reducing development time.</li>
      <li>Lucide Icons – A clean and customizable icon set to enhance UI design. Useful for buttons, navigation, and alerts.</li>
      <li>Hot Toast – A lightweight toast notification library to show alerts, errors, and success messages in your app.</li>
      <li>Zustand – A state management library for React that is simpler and more lightweight than Redux. Useful for global state management.</li>
      <li>Vite – A fast frontend build tool and development server, replacing Webpack for better performance and faster Hot Module Reloading (HMR).</li>
      <br/>
    </ul>
  <li>Backend</li>
    <ul>
      <br/>
      <li>Node.js – The runtime that allows JavaScript to run on the server side, handling backend logic and API requests.</li>
      <li>Express.js – A lightweight Node.js framework for building APIs. It manages routes, middleware, and server logic in a clean way.</li>
      <li>PostgreSQL – A powerful relational database used to store structured data for your app, accessed via SQL queries.</li>
      <br/>
    </ul>
  <li>Tools & Cloud</li>
    <ul>
      <br/>
      <li>Neon Tech – A cloud-native serverless PostgreSQL service. It provides a managed database solution with autoscaling, making deployment easier.</li>
      <li>Arcjet – A deployment and hosting service, likely used to deploy your backend and database with minimal setup.</li>
      <li>Postman – An API testing tool that helps you send requests to your backend, debug APIs, and test endpoints easily.</li>
      <br/>
    </ul>
</ul>

### Setup .env file

```js
PORT=3000

PGUSER=...
PGPASSWORD=...
PGHOST=...
PGDATABASE=...

ARCJET_KEY=...
ARCJET_ENV=development
```

### Run the API

```shell
npm run dev
```

### Run the frontend

```shell
cd frontend
npm run dev
```
<br/>
<p>...and last but not least, it's 100% responsive!</p>
