# npmtest-gulp-slim

#### basic test coverage for  [gulp-slim (v0.3.0)](https://github.com/cognitom/gulp-slim)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-slim.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-slim) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-slim.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-slim)

#### slim plugin for gulp

[![NPM](https://nodei.co/npm/gulp-slim.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-slim)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-slim/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-slim/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-slim/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-slim/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-slim/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-slim/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-slim/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-slim/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-slim/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-slim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-slim/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-slim/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-slim/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-slim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-slim/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-slim/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-slim/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-slim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-slim/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-slim/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-slim/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tsutomu Kawamura",
        "url": "http://librize.com/"
    },
    "bugs": {
        "url": "https://github.com/cognitom/gulp-slim/issues"
    },
    "contributors": [
        {
            "name": "Chang Wang",
            "url": "https://github.com/cheapsteak"
        },
        {
            "name": "Dominik Menke",
            "url": "https://github.com/dmke"
        },
        {
            "name": "yozzh",
            "url": "https://github.com/yozzh"
        }
    ],
    "dependencies": {
        "coffee-script": "^1.9.3",
        "gulp-util": "^3.0.6",
        "spawn-cmd": "0.0.2",
        "through2": "^0.6.5"
    },
    "description": "slim plugin for gulp",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-coffee": "^2.3.1",
        "mocha": "^2.2.5",
        "should": "^7.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "0e518a029398b1475efcd5ccd9b3095d6046a198",
        "tarball": "https://registry.npmjs.org/gulp-slim/-/gulp-slim-0.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "0db85f579977bcae0c886f0cf017d98621ef6ac3",
    "homepage": "https://github.com/cognitom/gulp-slim",
    "keywords": [
        "gulpplugin",
        "slim",
        "slim-lang",
        "template"
    ],
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "cognitom"
        }
    ],
    "name": "gulp-slim",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cognitom/gulp-slim.git"
    },
    "scripts": {
        "prepublish": "gulp coffee",
        "test": "mocha --compilers coffee:coffee-script/register -R spec"
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
