# boilerplate-vue3
vue3, vite, pinia, vue router, scss

## prerequisites
node v18.3+ and npm/yarn or similar

## setting up the project
_using yarn_
```
yarn create vite my-app --template vue
cd my-app
yarn add vue-router
yarn add pinia
yarn add -D sass
```

_using npm_
```
npm create vite@latest my-app -- --template vue
cd my-app
npm install vue-router
npm install pinia
npm install --save-dev sass
```

## copy project files
```
copy/paste from the other files in this repo, the other files are generated by the previous step!
```
_This should be the project file structure_
```
├── README.md
├── index.html
├── package.json
├── public
│   └── vite.svg
├── src
│   ├── App.vue
│   ├── assets
│   │   └── vue.svg
│   ├── views
│   │   ├── Home.vue
│   │   ├── About.vue
│   ├── main.js
│   ├── router
│   │   └── index.js
│   ├── store
│   │   └── index.js
│   ├── style.css
│   └── views
│       ├── About.vue
│       └── Home.vue
├── vite.config.js
└── yarn.lock
```

3. start up

_using yarn_

```
yarn dev
```

_using npm_
```
npm run dev
```
