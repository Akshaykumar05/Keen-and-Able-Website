# Project : **Keen-and-Able-Website**
* In this repository, we will document the project decription, how we build and what technologies we used. Let's begin with the components and deployment architecture of the project.

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

<p>In the navbar, we place the KeenAble logo along with links to the About, Services, Careers, and Contact Us pages.</p>

![image](https://i.postimg.cc/fLRWwfKG/Navbar.png)

### Clients

<p>In the Clients section, we feature all clients who have utilized services from Keen and Able.</p>

![image](https://i.postimg.cc/NfkTJPTT/client.png)

### Footer

<p>In the footer, we include the full address of KeenAble, along with links to the About, Services, and Contact pages. Our services encompass Web Development, Mobile App Development, Domain and Hosting, and General IT Consultation. Additionally, we provide links to our social media profiles.</p>

![image](https://i.postimg.cc/rpxJjS2t/footer.png)


### Hero

## Pages

### Contact Page

![image](https://i.postimg.cc/RFR23W6j/Keenable-Contact-Form.png)

### Home Page

![image](https://i.postimg.cc/fbKJbvCZ/Homepage1.png)

### Intro Page

![image](https://i.postimg.cc/mgK0Hxdy/about1.png)

![image](https://i.postimg.cc/1XRTQyts/about2.png)

### Career Page

![image](https://i.postimg.cc/Z5YN1FFQ/Screenshot-from-2024-02-23-11-43-23.png)


![image](https://i.postimg.cc/Dfqb0YxD/Screenshot-from-2024-02-23-11-54-01.png)


![image](https://i.postimg.cc/FR01f7Vc/Screenshot-from-2024-02-23-11-54-18.png)


### Services Page

![image](https://i.postimg.cc/zDSb28K3/service1.png)

## App.Js







