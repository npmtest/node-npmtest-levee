# npmtest-levee

#### basic test coverage for  [levee (v1.2.1)](https://github.com/krakenjs/levee)  [![npm package](https://img.shields.io/npm/v/npmtest-levee.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-levee) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-levee.svg)](https://travis-ci.org/npmtest/node-npmtest-levee)

#### A circuitbreaker implementation for Node.js

[![NPM](https://nodei.co/npm/levee.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/levee)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-levee/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-levee/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-levee/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-levee/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-levee/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-levee/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-levee/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-levee/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-levee/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-levee/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-levee/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-levee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-levee/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-levee/build/test-report.html](https://npmtest.github.io/node-npmtest-levee/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-levee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-levee/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-levee/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-levee/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-levee/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-levee/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-levee/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-levee/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Toth"
    },
    "bugs": {
        "url": "https://github.com/krakenjs/levee/issues"
    },
    "dependencies": {
        "hoek": "^2.4.1"
    },
    "description": "A circuitbreaker implementation for Node.js",
    "devDependencies": {
        "eslint": "^0.7.4",
        "istanbul": "^0.3.0",
        "tape": "^2.14.0",
        "wreck": "^3.0.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "d4862c32037aef9170241217fa407cbf3dc9baed",
        "tarball": "https://registry.npmjs.org/levee/-/levee-1.2.1.tgz"
    },
    "gitHead": "5107d7041d76e79ff513be9fdc9b8978140c8077",
    "homepage": "https://github.com/krakenjs/levee",
    "keywords": [
        "circuit",
        "breaker",
        "circuitbreaker",
        "levee"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "grawk"
        },
        {
            "name": "subeeshcbabu"
        },
        {
            "name": "tlivings"
        },
        {
            "name": "totherik"
        }
    ],
    "name": "levee",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krakenjs/levee.git"
    },
    "scripts": {
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "eslint index.js lib/*.js",
        "test": "tape test/*.js"
    },
    "version": "1.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
