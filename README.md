# npmtest-debug

#### test coverage for  [debug (v2.6.3)](https://github.com/visionmedia/debug#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-debug.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-debug) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-debug.svg)](https://travis-ci.org/npmtest/node-npmtest-debug)

#### small debugging utility

[![NPM](https://nodei.co/npm/debug.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/debug)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-debug/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-debug/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-debug/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-debug/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-debug/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-debug/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-debug/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-debug/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-debug/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-debug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-debug/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-debug/build/test-report.html](https://npmtest.github.io/node-npmtest-debug/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-debug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-debug/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-debug/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-debug/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-debug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-debug/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-debug/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-debug/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "browser": "./src/browser.js",
    "bugs": {
        "url": "https://github.com/visionmedia/debug/issues"
    },
    "component": {
        "scripts": {
            "debug/index.js": "browser.js",
            "debug/debug.js": "debug.js"
        }
    },
    "contributors": [
        {
            "name": "Nathan Rajlich",
            "url": "http://n8.io"
        },
        {
            "name": "Andrew Rhyne"
        }
    ],
    "dependencies": {
        "ms": "0.7.2"
    },
    "description": "small debugging utility",
    "devDependencies": {
        "browserify": "9.0.3",
        "chai": "^3.5.0",
        "concurrently": "^3.1.0",
        "coveralls": "^2.11.15",
        "eslint": "^3.12.1",
        "istanbul": "^0.4.5",
        "karma": "^1.3.0",
        "karma-chai": "^0.1.0",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sinon": "^1.0.5",
        "mocha": "^3.2.0",
        "mocha-lcov-reporter": "^1.2.0",
        "rimraf": "^2.5.4",
        "sinon": "^1.17.6",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0f7eb8c30965ec08c72accfa0130c8b79984141d",
        "tarball": "https://registry.npmjs.org/debug/-/debug-2.6.3.tgz"
    },
    "gitHead": "9dc30f8378cc12192635cc6a31f0d96bb39be8bb",
    "homepage": "https://github.com/visionmedia/debug#readme",
    "keywords": [
        "debug",
        "log",
        "debugger"
    ],
    "license": "MIT",
    "main": "./src/index.js",
    "maintainers": [
        {
            "name": "thebigredgeek"
        }
    ],
    "name": "debug",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/visionmedia/debug.git"
    },
    "scripts": {},
    "version": "2.6.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
