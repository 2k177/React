## NPM- Node Package Manager
	npm is a package manager for the JavaScript programming language maintained by npm, Inc. npm is the default package manager for the JavaScript runtime environment Node.js. It consists of a command line client, also called npm, and an online database of public and paid-for private packages, called the npm registry.

``` Verify using npm --version ```

``` npm init ```:
npm init is a convenient way of scaffolding your package. json; We may need to run it everytime you are starting a new project.

``` npm install ```:
npm install , however, installs your dependencies in node_modules folder. 
We may need to run this everytime you manually add a dependency to your package.

### To install a module globally,
``` npm install -g <module> ```

``` npm install -g cowsay ```

### To install a module locally
``` npm install <module> ```

``` npm install cowsay ```

### package.json:
The package.json file is the heart of any Node project. It records important metadata about a project which is required before publishing to NPM, and also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package

further info: https://docs.npmjs.com/cli/v9/configuring-npm/package-json



