## Prettier

Source page : https://prettier.io/docs/en/install.html

`npm install --save-dev --save-exact prettier`

`echo {}> .prettierrc.json`

Add `prettier --write .` in package.json scripts

<code>  
"scripts": {
"format": "prettier --write ."
},
</code>

Execute the command `npm run format`

## Eslint

ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.

Source page: https://eslint.org/docs/latest/use/getting-started

<code>
npm install --save-dev eslint
touch .eslintrc.js
</code>

Package.json
<code>  
"scripts": {
"format": "eslint \*.mjs"
},
</code>

execute `npm run lint`
