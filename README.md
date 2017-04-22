# npmtest-caniuse-api

#### basic test coverage for  [caniuse-api (v1.6.1)](https://github.com/nyalab/caniuse-api#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-caniuse-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-caniuse-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-caniuse-api.svg)](https://travis-ci.org/npmtest/node-npmtest-caniuse-api)

#### request the caniuse data to check browsers compatibilities

[![NPM](https://nodei.co/npm/caniuse-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/caniuse-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-caniuse-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-caniuse-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-caniuse-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-caniuse-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-caniuse-api/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-caniuse-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-caniuse-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-caniuse-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-caniuse-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-caniuse-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-caniuse-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-caniuse-api/build/test-report.html](https://npmtest.github.io/node-npmtest-caniuse-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-caniuse-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-caniuse-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-caniuse-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-caniuse-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-caniuse-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-caniuse-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-caniuse-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-caniuse-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "nyalab",
        "MoOx"
    ],
    "babel": {
        "presets": [
            "babel-preset-latest"
        ]
    },
    "bugs": {
        "url": "https://github.com/nyalab/caniuse-api/issues"
    },
    "dependencies": {
        "browserslist": "^1.3.6",
        "caniuse-db": "^1.0.30000529",
        "lodash.memoize": "^4.1.2",
        "lodash.uniq": "^4.5.0"
    },
    "description": "request the caniuse data to check browsers compatibilities",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-eslint": "^5.0.0",
        "babel-preset-latest": "^6.22.0",
        "babel-tape-runner": "^2.0.1",
        "jshint": "^2.5.10",
        "npmpub": "^3.1.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b534e7c734c4f81ec5fbe8aca2ad24354b962c6c",
        "tarball": "https://registry.npmjs.org/caniuse-api/-/caniuse-api-1.6.1.tgz"
    },
    "files": [
        "dist"
    ],
    "gitHead": "a0d94a2d08b7d5de48e8404d63182764999734cc",
    "homepage": "https://github.com/nyalab/caniuse-api#readme",
    "keywords": [
        "caniuse",
        "browserslist"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "nyalab"
        }
    ],
    "name": "caniuse-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nyalab/caniuse-api.git"
    },
    "scripts": {
        "build": "babel src --out-dir dist",
        "lint": "jshint src",
        "prepublish": "npm run build",
        "release": "npmpub",
        "test": "npm run lint && babel-tape-runner test/*.js | tap-spec"
    },
    "version": "1.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
