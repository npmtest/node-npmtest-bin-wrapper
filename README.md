# npmtest-bin-wrapper

#### basic test coverage for  [bin-wrapper (v3.0.2)](https://github.com/kevva/bin-wrapper#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bin-wrapper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bin-wrapper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bin-wrapper.svg)](https://travis-ci.org/npmtest/node-npmtest-bin-wrapper)

#### Binary wrapper that makes your programs seamlessly available as local dependencies

[![NPM](https://nodei.co/npm/bin-wrapper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bin-wrapper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bin-wrapper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bin-wrapper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bin-wrapper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bin-wrapper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bin-wrapper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bin-wrapper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bin-wrapper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bin-wrapper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bin-wrapper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bin-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bin-wrapper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bin-wrapper/build/test-report.html](https://npmtest.github.io/node-npmtest-bin-wrapper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bin-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bin-wrapper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bin-wrapper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bin-wrapper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bin-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bin-wrapper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bin-wrapper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bin-wrapper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Mårtensson",
        "url": "https://github.com/kevva"
    },
    "bugs": {
        "url": "https://github.com/kevva/bin-wrapper/issues"
    },
    "dependencies": {
        "bin-check": "^2.0.0",
        "bin-version-check": "^2.1.0",
        "download": "^4.0.0",
        "each-async": "^1.1.1",
        "lazy-req": "^1.0.0",
        "os-filter-obj": "^1.0.0"
    },
    "description": "Binary wrapper that makes your programs seamlessly available as local dependencies",
    "devDependencies": {
        "ava": "^0.0.4",
        "nock": "^2.6.0",
        "rimraf": "^2.2.8"
    },
    "directories": {},
    "dist": {
        "shasum": "67d3306262e4b1a5f2f88ee23464f6a655677aeb",
        "tarball": "https://registry.npmjs.org/bin-wrapper/-/bin-wrapper-3.0.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "8a777c36019c9cc66bd1d1999d01ffd5e9167601",
    "homepage": "https://github.com/kevva/bin-wrapper#readme",
    "keywords": [
        "bin",
        "check",
        "local",
        "wrapper"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kevva"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "bin-wrapper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kevva/bin-wrapper.git"
    },
    "scripts": {
        "test": "node test/test.js"
    },
    "version": "3.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
