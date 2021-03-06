# Shopping Cart 🛒

Captura de la app <br />
[Enlace a la App online](...) <br />
[Enlace al proyecto en GitHub](https://github.com/leireriel/my-react-redux-boilerplate)

## 👀 What is this?

This is a ... <br />
Enjoy it! 🔥

## 📅 What am I working on now

Creating project structure :)

## 🏗️ Getting started

You need to have installed [Node.js](https://nodejs.org/), and then:

1. `$ git clone https://github.com/leireriel/my-react-redux-boilerplate.git`
2. `$ npm i`
3. `$ npm start` + open `http://localhost:3000/`

## ⛩️ Structure

```
shopping-cart
├── node_modules
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src
│   ├── actions (redux)
│   ├── assets
│   │   ├── fonts
│   │   └── images
│   ├── components
│   │   ├── Counter
│   │   └── Button
│   ├── constants
│   ├── layouts
│   │   ├── Footer
│   │   ├── Header
│   │   └── Main
│   ├── modals
│   ├── reducers (redux)
│   │   ├── counter.js
│   │   ├── index.js
│   │   └── isLogged.js
│   ├── routes
│   │   ├── App
│   │   └── Shop
│   ├── services
│   ├── styles
│   │   ├── _base.scss
│   │   ├── _breakpoints.scss
│   │   ├── _colors.scss
│   │   ├── _fonts.scss
│   │   └── index.scss
│   ├── utils
|   └── index.js
├── tests
│   ├── App.test.js
|   └── setupTests.js
├── .babelrc
├── .env
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

## 📦 Dependencies

I used `Create React App` because it provides me with Webpack, Babel and ESLint configuration that is sufficient for my little project. It includes the following dependencies:
* React ⚛
* Webpack
* Babel
* ESLint
* Jest

If I wanted to modify the configutation of this modules I could run `$ npm run eject`.

Also I installed:
* [prop-types](https://www.npmjs.com/package/prop-types)
* [react-router-dom](https://www.npmjs.com/package/react-router-dom)
* [node-sass](https://www.npmjs.com/package/node-sass)
* [redux](https://www.npmjs.com/package/redux)
* [react-redux](https://www.npmjs.com/package/react-redux)


And this Babel plugin:
* [@babel/plugin-proposal-optional-chaining](https://babeljs.io/docs/en/babel-plugin-proposal-optional-chaining)

To consider:
* Note that I have set `NODE_PATH=src` in `.env` file, in order to allow absolute paths on imports.

## 💪 Challenges

...

## 💡 To Do

... <br />
usar optional-chaining <br />
redux <br />
Tests

## 🔧 Production build

To generate a production ready version on `docs` folder:

1. Add `"homepage": "./"` in `package.json`
2. Make sure there are only `https` in your project (replace all references to http with https)
3. `$ npm run build` + `$ mv build docs`

Now you can upload your public folder to GitHub Pages or similar :)

## 🤜🤛 Suggestions

All suggestions are welcome, please open an issue 💜
