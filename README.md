# npmtest-excel-stream

#### basic test coverage for  [excel-stream (v1.1.1)](https://github.com/dominictarr/excel-stream)  [![npm package](https://img.shields.io/npm/v/npmtest-excel-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-excel-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-excel-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-excel-stream)

#### convert a stream of xls or xlsx into json on the command line or in node

[![NPM](https://nodei.co/npm/excel-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/excel-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-excel-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-excel-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-excel-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-excel-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-excel-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-excel-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-excel-stream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-excel-stream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-excel-stream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-excel-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-excel-stream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-excel-stream/build/test-report.html](https://npmtest.github.io/node-npmtest-excel-stream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-excel-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-excel-stream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-excel-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-excel-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-excel-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-excel-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-excel-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-excel-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "http://dominictarr.com"
    },
    "bin": {
        "excel-stream": "index.js"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/excel-stream/issues"
    },
    "dependencies": {
        "JSONStream": "^1.0.4",
        "concat-stream": "^1.4.6",
        "csv-stream": "~0.1.3",
        "duplexer": "~0.1.1",
        "j": "^0.4.3",
        "minimist": "^1.1.1",
        "osenv": "^0.1.3",
        "through": "~2.3.4",
        "win-spawn": "^2.0.0"
    },
    "description": "convert a stream of xls or xlsx into json on the command line or in node",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "1ba0eed90f89a31d50ddb55089b6b32f5e43f8c4",
        "tarball": "https://registry.npmjs.org/excel-stream/-/excel-stream-1.1.1.tgz"
    },
    "gitHead": "129fe0b69a69ab08a0cd09aa16ae70cc1622ca85",
    "homepage": "https://github.com/dominictarr/excel-stream",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        },
        {
            "name": "maxogden"
        },
        {
            "name": "guumaster"
        }
    ],
    "name": "excel-stream",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/excel-stream.git"
    },
    "scripts": {
        "test": "set -e; for t in test/*.js; do node $t; done"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
