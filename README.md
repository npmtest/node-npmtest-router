# npmtest-router

#### basic test coverage for  [router (v1.3.0)](https://github.com/pillarjs/router#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-router.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-router) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-router.svg)](https://travis-ci.org/npmtest/node-npmtest-router)

#### Simple middleware-style router

[![NPM](https://nodei.co/npm/router.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/router)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-router/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-router/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-router/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-router/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-router/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-router/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-router/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-router/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-router/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-router/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-router/build/test-report.html](https://npmtest.github.io/node-npmtest-router/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-router/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-router/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-router/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-router/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-router/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-router/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/router/issues"
    },
    "contributors": [
        {
            "name": "Blake Embrey"
        }
    ],
    "dependencies": {
        "array-flatten": "2.1.1",
        "debug": "2.6.1",
        "methods": "~1.1.2",
        "parseurl": "~1.3.1",
        "path-to-regexp": "0.1.7",
        "setprototypeof": "1.0.3",
        "utils-merge": "1.0.0"
    },
    "description": "Simple middleware-style router",
    "devDependencies": {
        "after": "0.8.2",
        "finalhandler": "1.0.0",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "15b24075c1de4a3d3f39808c5d7344a1564417c8",
        "tarball": "https://registry.npmjs.org/router/-/router-1.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "lib/",
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "89aacfa4b74279b4f09632d7dc90b1ef61e91dcc",
    "homepage": "https://github.com/pillarjs/router#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "router",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/router.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
