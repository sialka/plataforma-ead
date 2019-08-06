# Coding Style + ESLint

./node_modules/eslint/bin/eslint.js --init

>To check syntax and find problems
>CommonJS (require/exports)
>None of these
>Node
>JSON


## Usando

./node_modules/eslint/bin/eslint.js ./src/index.js

## Regras

https://github.com/airbnb/javascript

## Instalando

https://www.npmjs.com/package/eslint-config-airbnb-base

npm install -g npx
npx install-peerdeps --dev eslint-config-airbnb-base

**.eslintrc.json**
{
  "extends": "airbnb-base"
}

**package.json**
...
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "start": "nodemon src/index",
  "eslint": "eslint ./src/**/*.js"
},
...

##**Dependências**

- [x] npm install --save dotenv-safe
- [x] npm install --save mongoose
