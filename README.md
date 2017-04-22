# npmtest-node-mariadb

#### basic test coverage for  [node-mariadb (v0.1.1)](http://miketokyo.com)  [![npm package](https://img.shields.io/npm/v/npmtest-node-mariadb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-mariadb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-mariadb.svg)](https://travis-ci.org/npmtest/node-npmtest-node-mariadb)

#### A pure javascript client for mariadb

[![NPM](https://nodei.co/npm/node-mariadb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-mariadb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-mariadb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-mariadb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-mariadb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-mariadb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-mariadb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-mariadb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-mariadb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-mariadb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-mariadb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-mariadb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-mariadb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-mariadb/build/test-report.html](https://npmtest.github.io/node-npmtest-node-mariadb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-mariadb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-mariadb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-mariadb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-mariadb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-mariadb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-mariadb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-mariadb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-mariadb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "noppoMan",
        "url": "http://miketokyo.com"
    },
    "bugs": {
        "url": "https://github.com/noppoMan/node-mariadb/issues"
    },
    "contributors": [],
    "dependencies": {
        "async": "~0.2.9",
        "mysql": "~2.0.0-alpha9",
        "should": "~2.0.2"
    },
    "description": "A pure javascript client for mariadb",
    "devDependencies": {
        "async": "0.2.9",
        "mysql": "2.0.0-alpha9",
        "should": "2.0.2"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "904a5b8b0f37cf32bad7e62ce2716edf28abe3cb",
        "tarball": "https://registry.npmjs.org/node-mariadb/-/node-mariadb-0.1.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "homepage": "http://miketokyo.com",
    "keywords": [
        "mariadb",
        "handlersocket",
        "non-blocking"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "noppoman"
        }
    ],
    "name": "node-mariadb",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/noppoMan/node-mariadb.git"
    },
    "scripts": {
        "test": "find ./test -name *_test.js | xargs mocha --reporter spec"
    },
    "version": "0.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
