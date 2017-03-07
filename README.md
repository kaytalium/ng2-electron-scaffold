# ng2-electron-scaffold

[![Build Status](https://travis-ci.org/kaytalium/ng2-electron-scaffold.svg?branch=master)](https://travis-ci.org/kaytalium/ng2-electron-scaffold)
[![license](https://img.shields.io/github/license/kaytalium/ng2-electron-scaffold.svg)](LICENSE)
[![GitHub tag](https://img.shields.io/github/tag/kaytalium/ng2-electron-scaffold.svg)]()

Using Angular 2 with Electron to create a desktop application 

This setup is using systemjs as the module loader, also note all the js files are compiled to the dist folder this allow for easier navigation in the app folder.

After the project is download make sure to npm run tsc then npm serve.

```javascript

$ npm run tsc
$ npm start

```

If you run npm serve before the npm tsc you will have to use ctrl + r for windows to reload the window to see the index page. this only means that electron start up and request main.js in the dist folder before the project finsih building. 

Special thanks to [Denys Vuika](https://medium.com/@DenysVuika/using-angular-2-with-electron-a9fa0715cf12#.ey3prjuta")
