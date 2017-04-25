# npmtest-pify

#### basic test coverage for  [pify (v2.3.0)](https://github.com/sindresorhus/pify)  [![npm package](https://img.shields.io/npm/v/npmtest-pify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pify.svg)](https://travis-ci.org/npmtest/node-npmtest-pify)

#### Promisify a callback-style function

[![NPM](https://nodei.co/npm/pify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pify/build/test-report.html](https://npmtest.github.io/node-npmtest-pify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/pify/issues"
    },
    "dependencies": {},
    "description": "Promisify a callback-style function",
    "devDependencies": {
        "ava": "*",
        "pinkie-promise": "^1.0.0",
        "v8-natives": "0.0.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "ed141a6ac043a849ea588498e7dca8b15330e90c",
        "tarball": "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "2dd0d8b880e4ebcc5cc33ae126b02647418e4440",
    "homepage": "https://github.com/sindresorhus/pify",
    "keywords": [
        "promise",
        "promises",
        "promisify",
        "denodify",
        "denodeify",
        "callback",
        "cb",
        "node",
        "then",
        "thenify",
        "convert",
        "transform",
        "wrap",
        "wrapper",
        "bind",
        "to",
        "async",
        "es2015"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "pify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/pify.git"
    },
    "scripts": {
        "optimization-test": "node --allow-natives-syntax optimization-test.js",
        "test": "xo && ava && npm run optimization-test"
    },
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
