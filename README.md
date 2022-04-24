# Angular-create-app

Install the Angular CLI:

```
npm install -g @angular/cli
```

At the folder where you want to create the app, run the command:

```
ng new my-app
```

Angular app will ask the following questions:

```
Would you like to add Angular routing? We write: Y.

Luego el formato de stylesheet, en el cual seleccionamos CSS.
```

## Install bootstrap

Be sure to install it on the root folder:

```
npm install --save bootstrap
```

When the process is completed, Bootstrap will be installed inside the folder called `node_modules`.

Also, in the `package.json` file, we can be able to see the dependencies of bootstrap

Next, we need to add the bootstrap stylesheet to the `angular.json` file as follows:

```
"styles": [
   "node_modules/bootstrap/dist/css/bootstrap.min.css",
   "src/styles.css"
],
```

## Run the app

Go to the root folder of the app and run the following command:

```
ng serve
```

And you'll see

```
** Angular Live Development Server is listening on localhost:4200, open your
browser on http://localhost:4200/ **
i ｢wdm｣: Compiled successfully.
```

## VSCode extensions

We can install the VSCode extension `ng-vscode` to get the Angular language support.

- Angular Essentials (by John Papa)
- Angular Files (by Alexander Ivanichev)
