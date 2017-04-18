# api documentation for  [trianglify (v1.0.1)](https://github.com/qrohlf/trianglify)  [![npm package](https://img.shields.io/npm/v/npmdoc-trianglify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-trianglify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-trianglify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-trianglify)
#### Trianglify is a javascript library for generating colorful triangle meshes that can be used as SVG images and CSS backgrounds.

[![NPM](https://nodei.co/npm/trianglify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/trianglify)

- [https://npmdoc.github.io/node-npmdoc-trianglify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-trianglify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-trianglify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-trianglify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-trianglify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-trianglify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Quinn Rohlf"
    },
    "browser": {
        "jsdom": false,
        "canvas": false
    },
    "bugs": {
        "url": "https://github.com/qrohlf/trianglify/issues"
    },
    "dependencies": {
        "canvas": "^1.3.0",
        "chroma-js": "^0.6.3",
        "colors": "^1.1.2",
        "delaunay-fast": "^1.0.1",
        "gulp": "^3.9.1",
        "jsdom": "^7.0.2",
        "seedrandom": "^2.3.11"
    },
    "description": "Trianglify is a javascript library for generating colorful triangle meshes that can be used as SVG images and CSS backgrounds.",
    "devDependencies": {
        "browserify": "^9.0.3",
        "chai": "^2.1.0",
        "del": "^0.1.1",
        "gulp": "^3.8.6",
        "gulp-bump": "^0.1.11",
        "gulp-filter": "^1.0.2",
        "gulp-git": "^0.5.2",
        "gulp-jshint": "^1.7.1",
        "gulp-mocha": "^1.1.1",
        "gulp-rename": "^1.2.0",
        "gulp-sourcemaps": "^1.5.0",
        "gulp-tag-version": "^1.1.0",
        "gulp-uglify": "^0.3.1",
        "jshint-stylish": "^0.4.0",
        "mocha": "^2.1.0",
        "node-notifier": "^4.1.2",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.0.0"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "a9c00cb49f3ba33e39acc8396abf0cd95c963146",
        "tarball": "https://registry.npmjs.org/trianglify/-/trianglify-1.0.1.tgz"
    },
    "gitHead": "049ae6caf688bdd449a26f23bc3dd7477ecc55ff",
    "homepage": "https://github.com/qrohlf/trianglify",
    "keywords": [
        "svg",
        "d3.js",
        "visualization"
    ],
    "license": "GPL-3.0",
    "main": "lib/trianglify.js",
    "maintainers": [
        {
            "name": "qrohlf"
        }
    ],
    "name": "trianglify",
    "npmFileMap": [
        {
            "basePath": "dist",
            "files": [
                "trianglify.min.js"
            ]
        }
    ],
    "npmName": "trianglify",
    "optionalDependencies": {
        "canvas": "^1.3.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/qrohlf/trianglify.git"
    },
    "scripts": {
        "postinstall": "node scripts/postinstall.js",
        "start": "gulp",
        "test": "mocha test/test.js"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
