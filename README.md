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
npm create-react-app KeenAble
```
```
cd KeenAble
```
```
npm start
```

## Dependencies

### tailwindcss

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

