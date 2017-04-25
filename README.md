# npmdoc-xbox-controller

#### basic api documentation for  [xbox-controller (v0.7.0)](https://github.com/andrew/node-xbox-controller)  [![npm package](https://img.shields.io/npm/v/npmdoc-xbox-controller.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-xbox-controller) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-xbox-controller.svg)](https://travis-ci.org/npmdoc/node-npmdoc-xbox-controller)

#### Xbox controller for node

[![NPM](https://nodei.co/npm/xbox-controller.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xbox-controller)

- [https://npmdoc.github.io/node-npmdoc-xbox-controller/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Andrew Nesbitt <andrewnez@gmail.com> (http://andrew.github.io)",
    "name": "xbox-controller",
    "description": "Xbox controller for node",
    "version": "0.7.0",
    "os": [
        "darwin",
        "linux",
        "win32"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/andrew/node-xbox-controller.git"
    },
    "homepage": "https://github.com/andrew/node-xbox-controller",
    "keywords": [
        "xbox",
        "controller",
        "gaming"
    ],
    "bugs": {
        "url": "https://github.com/andrew/node-xbox-controller/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/andrew/node-xbox-controller/blob/master/LICENSE"
        }
    ],
    "main": "./lib/xbox.js",
    "dependencies": {
        "lodash": "~2.4.1",
        "node-hid": "~0.4.0",
        "chalk": "~0.5.1"
    },
    "scripts": {
        "test": "node ./tests/test.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
