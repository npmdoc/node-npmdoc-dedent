# npmdoc-dedent

#### basic api documentation for  [dedent (v0.7.0)](https://github.com/dmnd/dedent)  [![npm package](https://img.shields.io/npm/v/npmdoc-dedent.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dedent) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dedent.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dedent)

#### An ES6 string tag that strips indentation from multi-line strings

[![NPM](https://nodei.co/npm/dedent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dedent)

- [https://npmdoc.github.io/node-npmdoc-dedent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dedent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dedent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dedent/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dedent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dedent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Desmond Brand",
        "url": "http://desmondbrand.com"
    },
    "bugs": {
        "url": "https://github.com/dmnd/dedent/issues"
    },
    "dependencies": {},
    "description": "An ES6 string tag that strips indentation from multi-line strings",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-es2016": "^6.22.0",
        "babel-preset-es2017": "^6.22.0",
        "eslint": "^3.14.1",
        "jest": "^18.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2495ddbaf6eb874abb0e1be9df22d2e5a544326c",
        "tarball": "https://registry.npmjs.org/dedent/-/dedent-0.7.0.tgz"
    },
    "files": [
        "dist/dedent.js",
        "LICENSE"
    ],
    "gitHead": "1cae3207449edba5e6d8588f3670bb03e2ad92a0",
    "homepage": "https://github.com/dmnd/dedent",
    "keywords": [
        "dedent",
        "tag",
        "multi-line string",
        "es6"
    ],
    "license": "MIT",
    "main": "dist/dedent.js",
    "maintainers": [
        {
            "name": "dmnd"
        }
    ],
    "name": "dedent",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dmnd/dedent.git"
    },
    "scripts": {
        "build": "babel dedent.js --out-file dist/dedent.js",
        "lint": "eslint dedent.js __tests__",
        "test": "jest"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
