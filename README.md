# npmdoc-babel-plugin-transform-imports

#### api documentation for  [babel-plugin-transform-imports (v1.2.0)](https://bitbucket.org/amctheatres/babel-transform-imports)  [![npm package](https://img.shields.io/npm/v/npmdoc-babel-plugin-transform-imports.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babel-plugin-transform-imports) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babel-plugin-transform-imports.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babel-plugin-transform-imports)

#### Transforms member style imports (import {x} from 'y') into default style imports (import x from 'y/lib/x')

[![NPM](https://nodei.co/npm/babel-plugin-transform-imports.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-transform-imports)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-transform-imports/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-transform-imports/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-transform-imports/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-transform-imports/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babel-plugin-transform-imports/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babel-plugin-transform-imports/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "babel-plugin-transform-imports",
    "version": "1.2.0",
    "description": "Transforms member style imports (import {x} from 'y') into default style imports (import x from 'y/lib/x')",
    "keywords": [
        "babel",
        "transform",
        "import",
        "react-bootstrap",
        "lodash"
    ],
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://bitbucket.org/amctheatres/babel-transform-imports.git"
    },
    "homepage": "https://bitbucket.org/amctheatres/babel-transform-imports",
    "scripts": {
        "test": "node_modules/.bin/mocha --compilers js:babel-register"
    },
    "author": "AMC Theatres",
    "license": "ISC",
    "dependencies": {
        "babel-types": "^6.6.0",
        "lodash.kebabcase": "^4.0.1"
    },
    "devDependencies": {
        "babel-core": "^6.6.0",
        "babel-preset-es2015": "^6.6.0",
        "mocha": "^2.4.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
