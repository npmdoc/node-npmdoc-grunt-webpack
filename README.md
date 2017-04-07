# api documentation for  [grunt-webpack (v2.0.1)](https://github.com/webpack-contrib/grunt-webpack)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-webpack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-webpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-webpack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-webpack)
#### Use webpack with grunt.

[![NPM](https://nodei.co/npm/grunt-webpack.png?downloads=true)](https://www.npmjs.com/package/grunt-webpack)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-webpack/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt-webpack_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-webpack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-webpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-webpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "ava": {
        "files": [
            "**/tests/**/*.js",
            "!**/utils/**/*",
            "!**/fixtures/**/*",
            "!**/tmp/**/*"
        ]
    },
    "bugs": {
        "url": "https://github.com/webpack-contrib/grunt-webpack/issues"
    },
    "dependencies": {
        "lodash": "^4.7.0"
    },
    "description": "Use webpack with grunt.",
    "devDependencies": {
        "ava": "^0.17.0",
        "babel-core": "^6.17.0",
        "babel-loader": "^6.2.9",
        "babel-preset-latest": "^6.16.0",
        "codecov": "^1.0.1",
        "eslint": "^3.6.1",
        "fs-extra": "^2.0.0",
        "glob": "^7.0.5",
        "grunt": "^1.0.0",
        "nyc": "^10.0.0",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "84c5d9373ade88468285de787021c42a97d5306c",
        "tarball": "https://registry.npmjs.org/grunt-webpack/-/grunt-webpack-2.0.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "src",
        "tasks"
    ],
    "gitHead": "5b75ce91a830663e3735731b63d0ae9d78e4ab95",
    "homepage": "https://github.com/webpack-contrib/grunt-webpack",
    "keywords": [
        "gruntplugin"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "bebraw",
            "email": "bebraw@gmail.com"
        },
        {
            "name": "chiplay",
            "email": "chiplay@mac.com"
        },
        {
            "name": "d3viant0ne",
            "email": "wiens.joshua@gmail.com"
        },
        {
            "name": "danez",
            "email": "daniel@tschinder.de"
        },
        {
            "name": "ericclemmons",
            "email": "eric@smarterspam.com"
        },
        {
            "name": "jhnns",
            "email": "mail@johannesewald.de"
        },
        {
            "name": "sokra",
            "email": "tobias.koppers@googlemail.com"
        },
        {
            "name": "thelarkinn",
            "email": "sean.larkin@cuw.edu"
        }
    ],
    "name": "grunt-webpack",
    "nyc": {
        "include": [
            "src/",
            "tasks/"
        ]
    },
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "^2.1.0-beta || ^2.2.0-rc || ^2.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/webpack-contrib/grunt-webpack.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=json && codecov -f coverage/coverage-final.json",
        "lint": "eslint src tasks",
        "preversion": "npm test",
        "test": "npm run lint && npm run test-only",
        "test-ci": "nyc npm run test-only",
        "test-only": "ava"
    },
    "version": "2.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt-webpack](#apidoc.module.grunt-webpack)



# <a name="apidoc.module.grunt-webpack"></a>[module grunt-webpack](#apidoc.module.grunt-webpack)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
