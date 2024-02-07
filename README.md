# Keen-and-Able-Website

## Node Js

**Node.js is a cross-platform, open-source JavaScript runtime environment that can run on Windows, Linux, Unix, macOS, and more. Node.js runs on the V8 JavaScript engine, and executes JavaScript code outside a web browser.**

```
sudo apt update
```
```
sudo apt install nodejs
```
```
node -v
```
## NPM

**npm is a package manager for the JavaScript programming language maintained by npm, Inc. npm is the default package manager for the JavaScript runtime environment Node.js and is included as a recommended feature in the Node.js installer.**

```
sudo apt install npm
```

## React Js

**React is a free and open-source front-end JavaScript library for building user interfaces or UI components. It is maintained by Meta and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.**

###  Install Create-React-App

```
npx create-react-app KeenAble
```
```
cd KeenAble
```
```
npm start
```

## Dependencies

### 1. Tailwindcss

**Tailwind CSS differs from other CSS frameworks like Bootstrap in that it doesn't provide predefined classes for elements like buttons or tables. Instead, it provides a set of opinionated, single-purpose utility classes that can be used directly inside markup to design an element.**

```
npm install -D tailwindcss
npm tailwindcss init
```

***Add the paths to all of your template files in your tailwind.config.js file.***

<p>Add the paths to all of your template files in your tailwind.config.js file.</p>

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

***Add the Tailwind directives to your index.CSS***

<p>Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.</p>

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 2. Axios

<p>Axios, which is a popular library is mainly used to send asynchronous HTTP requests to REST endpoints. This library is very useful to perform CRUD operations.</p>

<ol>
  <li>This popular library is used to communicate with the backend. Axios supports the Promise API, native to JS ES6.</li>
  <li>Using Axios we make API requests in our application. Once the request is made we get the data in Return, and then we use this data in our project. </li>
  <li>This library is very popular among developers. You can check on GitHub and you will find 78k stars on it. </li>
</ol>

```
npm install axios
```

### Pages We make in Keen and Able Website

## Components

### Navbar

### Clients

### Footer

### Hero

## Pages

### Contact Page

### Home Page

### Intro Page

### Career Page

### Services Page

## App.Js







