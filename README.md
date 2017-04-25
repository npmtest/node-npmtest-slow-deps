# npmtest-slow-deps

#### basic test coverage for  [slow-deps (v1.4.0)](https://github.com/nolanlawson/slow-deps#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-slow-deps.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slow-deps) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slow-deps.svg)](https://travis-ci.org/npmtest/node-npmtest-slow-deps)

#### Measure which dependencies in a project are slowest to install

[![NPM](https://nodei.co/npm/slow-deps.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slow-deps)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slow-deps/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slow-deps/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slow-deps/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slow-deps/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slow-deps/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-slow-deps/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-slow-deps/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slow-deps/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slow-deps/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slow-deps/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slow-deps/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slow-deps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slow-deps/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slow-deps/build/test-report.html](https://npmtest.github.io/node-npmtest-slow-deps/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slow-deps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slow-deps/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slow-deps/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slow-deps/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slow-deps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slow-deps/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slow-deps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slow-deps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nolan Lawson"
    },
    "bin": {
        "slow-deps": "index.js"
    },
    "bugs": {
        "url": "https://github.com/nolanlawson/slow-deps/issues"
    },
    "dependencies": {
        "any-shell-escape": "^0.1.1",
        "child-process-promise": "^1.1.0",
        "denodeify": "^1.2.1",
        "get-folder-size": "^1.0.0",
        "js-extend": "^1.0.1",
        "lie": "^3.1.0",
        "math-sum": "^1.0.0",
        "ncp": "^2.0.0",
        "performance-now": "^0.2.0",
        "prettier-bytes": "^1.0.3",
        "pretty-ms": "^2.1.0",
        "progress": "^1.1.8",
        "tablify": "^0.1.5",
        "temp": "^0.8.3",
        "yargs": "^4.7.1"
    },
    "description": "Measure which dependencies in a project are slowest to install",
    "devDependencies": {
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5efba127e5b8110d2ac96ac962e8d0e2061671c6",
        "tarball": "https://registry.npmjs.org/slow-deps/-/slow-deps-1.4.0.tgz"
    },
    "files": [],
    "gitHead": "1adcb4964cd07f18aa0ebbfdc884586f01e0bee6",
    "homepage": "https://github.com/nolanlawson/slow-deps#readme",
    "keywords": [
        "slow",
        "dependencies",
        "measure",
        "npm",
        "install"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "nolanlawson"
        }
    ],
    "name": "slow-deps",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nolanlawson/slow-deps.git"
    },
    "scripts": {
        "test": "standard"
    },
    "version": "1.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
