# npmtest-range-parser

#### test coverage for  [range-parser (v1.2.0)](https://github.com/jshttp/range-parser)  [![npm package](https://img.shields.io/npm/v/npmtest-range-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-range-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-range-parser.svg)](https://travis-ci.org/npmtest/node-npmtest-range-parser)

#### Range header field string parser

[![NPM](https://nodei.co/npm/range-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/range-parser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-range-parser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-range-parser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-range-parser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-range-parser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-range-parser/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-range-parser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-range-parser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-range-parser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-range-parser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-range-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-range-parser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-range-parser/build/test-report.html](https://npmtest.github.io/node-npmtest-range-parser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-range-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-range-parser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-range-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-range-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-range-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-range-parser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-range-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-range-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/jshttp/range-parser/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "James Wyatt Cready"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {},
    "description": "Range header field string parser",
    "devDependencies": {
        "eslint": "2.11.1",
        "eslint-config-standard": "5.3.1",
        "eslint-plugin-promise": "1.1.0",
        "eslint-plugin-standard": "1.3.2",
        "istanbul": "0.4.3",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "f49be6b487894ddc40dcc94a322f611092e00d5e",
        "tarball": "https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "0665aca31639d799dee1d35fb10970799559ec48",
    "homepage": "https://github.com/jshttp/range-parser",
    "keywords": [
        "range",
        "parser",
        "http"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "range-parser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/range-parser.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
