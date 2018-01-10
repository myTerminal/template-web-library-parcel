# template-library-parcel

[![Code Climate](https://codeclimate.com/github/myTerminal/template-library-parcel.png)](https://codeclimate.com/github/myTerminal/template-library-parcel)
[![bitHound Overall Score](https://www.bithound.io/github/myTerminal/template-library-parcel/badges/score.svg)](https://www.bithound.io/github/myTerminal/template-library-parcel)
[![bitHound Code](https://www.bithound.io/github/myTerminal/template-library-parcel/badges/code.svg)](https://www.bithound.io/github/myTerminal/template-library-parcel)  
[![Dependency Status](https://david-dm.org/myTerminal/template-library-parcel.svg)](https://david-dm.org/myTerminal/template-library-parcel)
[![devDependency Status](https://david-dm.org/myTerminal/template-library-parcel/dev-status.svg)](https://david-dm.org/myTerminal/template-library-parcel#info=devDependencies)
[![peer Dependency Status](https://david-dm.org/myTerminal/template-library-parcel/peer-status.svg)](https://david-dm.org/myTerminal/template-library-parcel#info=peerDependencies)  
[![License](https://img.shields.io/badge/LICENSE-GPL%20v3.0-blue.svg)](https://www.gnu.org/licenses/gpl.html)
[![Gratipay](http://img.shields.io/gratipay/myTerminal.svg)](https://gratipay.com/myTerminal)  

A template to create front-end libraries with [Parcel.js](https://parceljs.org) as the bundler [in-progress]

## Technologies

### Web

 - [jQuery](https://jquery.com/) (sample dependency)
 - [ES2015](http://es6-features.org/)
 - [Less CSS](http://lesscss.org/)

### Module bundler: Parcel

All you need is [parcel-bundler](https://www.npmjs.com/package/parcel-bundler) and it takes care of almost everything implicitly.

#### A few other packages

 - [babel-preset-env](https://www.npmjs.com/package/babel-preset-env) to transpile ES2015 scripts to regular JavaScript but no [babel-core](https://www.npmjs.com/package/babel-core)!
 - [jshint](https://www.npmjs.com/package/jshint) for running JSHint to lint JavaScript files
 - [jscs](https://www.npmjs.com/package/jscs) for checking code styles in JavaScript files
 - [less](https://www.npmjs.com/package/less) to help parcel-bundler with transpilation of Less CSS into regular CSS (if you do not include this, parcel-bundle automatically adds it)

#### Commands

 - `npm run develop` to instruct parcel-bundler to build the library and keep watching for file changes within source.
 - `npm run build` to instruct parcel-bundler to build the library and stop.  
 - `npm run lint` to run jscs and jshint on all JavaScript source files.

## To-Do

 - Find a way to generate source-maps
 - Find a way to build UMD modules
 - Find a way to write and run tests