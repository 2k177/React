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
