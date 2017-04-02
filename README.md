# api documentation for  [clean-css (v4.0.10)](https://github.com/jakubpawlowicz/clean-css)  [![npm package](https://img.shields.io/npm/v/npmdoc-clean-css.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-clean-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-clean-css.svg)](https://travis-ci.org/npmdoc/node-npmdoc-clean-css)
#### A well-tested CSS minifier

[![NPM](https://nodei.co/npm/clean-css.png?downloads=true)](https://www.npmjs.com/package/clean-css)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clean-css/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-clean-css_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clean-css/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-clean-css/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Jakub Pawlowicz",
        "email": "contact@jakubpawlowicz.com",
        "url": "http://twitter.com/jakubpawlowicz"
    },
    "bugs": {
        "url": "https://github.com/jakubpawlowicz/clean-css/issues"
    },
    "dependencies": {
        "source-map": "0.5.x"
    },
    "description": "A well-tested CSS minifier",
    "devDependencies": {
        "browserify": "13.x",
        "http-proxy": "1.x",
        "jshint": "2.x",
        "nock": "9.x",
        "server-destroy": "1.x",
        "uglify-js": ">=2.6.1",
        "vows": "0.8.x"
    },
    "directories": {},
    "dist": {
        "shasum": "6be448d6ba8c767654ebe11f158b97a887cb713f",
        "tarball": "https://registry.npmjs.org/clean-css/-/clean-css-4.0.10.tgz"
    },
    "engines": {
        "node": ">= 4.0"
    },
    "files": [
        "lib",
        "History.md",
        "index.js",
        "LICENSE"
    ],
    "gitHead": "4d024a8b96a872cc77afef24638931d3275c6eeb",
    "homepage": "https://github.com/jakubpawlowicz/clean-css",
    "keywords": [
        "css",
        "minifier"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "goalsmashers",
            "email": "jakub@goalsmashers.com"
        },
        {
            "name": "jakub.pawlowicz",
            "email": "contact@jakubpawlowicz.com"
        }
    ],
    "name": "clean-css",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jakubpawlowicz/clean-css.git"
    },
    "scripts": {
        "bench": "node ./test/bench.js",
        "browserify": "browserify --standalone CleanCSS index.js | uglifyjs --compress --mangle -o cleancss-browser.js",
        "check": "jshint .",
        "prepublish": "npm run check",
        "test": "vows"
    },
    "version": "4.0.10"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module clean-css](#apidoc.module.clean-css)



# <a name="apidoc.module.clean-css"></a>[module clean-css](#apidoc.module.clean-css)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
