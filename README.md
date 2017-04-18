# npmtest-steed

#### test coverage for  [steed (v1.1.3)](https://github.com/mcollina/steed#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-steed.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-steed) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-steed.svg)](https://travis-ci.org/npmtest/node-npmtest-steed)

#### horsepower for your modules

[![NPM](https://nodei.co/npm/steed.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/steed)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-steed/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-steed/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-steed/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-steed/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-steed/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-steed/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-steed/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-steed/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-steed/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-steed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-steed/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-steed/build/test-report.html](https://npmtest.github.io/node-npmtest-steed/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-steed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-steed/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-steed/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-steed/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-steed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-steed/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-steed/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-steed/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bugs": {
        "url": "https://github.com/mcollina/steed/issues"
    },
    "dependencies": {
        "fastfall": "^1.5.0",
        "fastparallel": "^2.2.0",
        "fastq": "^1.3.0",
        "fastseries": "^1.7.0",
        "reusify": "^1.0.0"
    },
    "description": "horsepower for your modules",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "fastbench": "^1.0.0",
        "istanbul": "^0.4.1",
        "neo-async": "^1.7.0",
        "standard": "^5.4.1",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "f1525dd5adb12eb21bf74749537668d625b9abc5",
        "tarball": "https://registry.npmjs.org/steed/-/steed-1.1.3.tgz"
    },
    "gitHead": "1bf30bbb18f5d7dae683009a01b40dbbb6636a6e",
    "homepage": "https://github.com/mcollina/steed#readme",
    "keywords": [
        "control",
        "flow",
        "async",
        "series",
        "parallel"
    ],
    "license": "MIT",
    "main": "steed.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "steed",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/steed.git"
    },
    "scripts": {
        "coverage": "istanbul cover tape test.js; cat coverage/lcov.info | coveralls",
        "test": "standard && tape test.js | tap-spec"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
