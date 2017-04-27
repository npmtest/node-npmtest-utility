# npmtest-utility

#### basic test coverage for  [utility (v1.12.0)](https://github.com/node-modules/utility)  [![npm package](https://img.shields.io/npm/v/npmtest-utility.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-utility) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-utility.svg)](https://travis-ci.org/npmtest/node-npmtest-utility)

#### A collection of useful utilities.

[![NPM](https://nodei.co/npm/utility.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/utility)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-utility/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-utility/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-utility/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-utility/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-utility/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-utility/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-utility/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-utility/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-utility/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-utility/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-utility/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-utility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-utility/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-utility/build/test-report.html](https://npmtest.github.io/node-npmtest-utility/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-utility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-utility/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-utility/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-utility/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-utility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-utility/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-utility/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-utility/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "url": "http://fengmk2.com"
    },
    "bugs": {
        "url": "https://github.com/node-modules/utility/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "http://fengmk2.com"
        },
        {
            "name": "dead_horse",
            "url": "https://github.com/dead-horse"
        },
        {
            "name": "haoxin",
            "url": "https://github.com/coderhaoxin"
        },
        {
            "name": "hui",
            "url": "https://github.com/leoner"
        },
        {
            "name": "Haoliang Gao",
            "url": "https://github.com/popomore"
        }
    ],
    "dependencies": {
        "copy-to": "~2.0.1",
        "escape-html": "~1.0.3"
    },
    "description": "A collection of useful utilities.",
    "devDependencies": {
        "autod": "*",
        "ava": "^0.14.0",
        "beautify-benchmark": "*",
        "benchmark": "^2.1.0",
        "contributors": "*",
        "jshint": "*",
        "moment": "^2.12.0",
        "nyc": "6",
        "object-assign": "^4.1.1",
        "optimized": "1"
    },
    "directories": {},
    "dist": {
        "shasum": "bd69307863a3884ee58821251215b9872fb84058",
        "tarball": "https://registry.npmjs.org/utility/-/utility-1.12.0.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "7ace74e85dbce6dbdd26ea54a988169132ed30a6",
    "homepage": "https://github.com/node-modules/utility",
    "keywords": [
        "utility",
        "util",
        "utils",
        "sha256",
        "sha1",
        "hash",
        "hex"
    ],
    "license": "MIT",
    "main": "lib/utility.js",
    "maintainers": [
        {
            "name": "fengmk2"
        },
        {
            "name": "dead_horse"
        }
    ],
    "name": "utility",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/utility.git",
        "web": "https://github.com/node-modules/utility"
    },
    "scripts": {
        "autod": "autod -w --prefix '~' -e benchmark",
        "ci": "npm run lint && npm run test-cov",
        "lint": "jshint .",
        "test": "npm run lint && npm run test-local",
        "test-cov": "nyc ava test/**/*.test.js && nyc report --reporter=lcov",
        "test-local": "ava test/**/*.test.js",
        "test-optimized": "node --allow-natives-syntax --trace_opt --trace_deopt test/optimized.js"
    },
    "version": "1.12.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
