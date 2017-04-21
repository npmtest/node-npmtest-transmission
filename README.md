# npmtest-transmission

#### basic test coverage for  transmission (v0.4.9)  [![npm package](https://img.shields.io/npm/v/npmtest-transmission.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-transmission) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-transmission.svg)](https://travis-ci.org/npmtest/node-npmtest-transmission)

#### API client for transmissionbt

[![NPM](https://nodei.co/npm/transmission.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/transmission)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-transmission/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-transmission/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-transmission/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-transmission/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-transmission/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-transmission/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-transmission/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-transmission/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-transmission/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-transmission/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-transmission/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-transmission/build/test-report.html](https://npmtest.github.io/node-npmtest-transmission/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-transmission/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-transmission/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-transmission/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-transmission/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-transmission/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-transmission/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-transmission/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-transmission/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Tim <git@mangoraft.com",
    "contributors": [
        "Alex Bepple"
    ],
    "name": "transmission",
    "description": "API client for transmissionbt",
    "version": "0.4.9",
    "scripts": {
        "test": "mocha --ui bdd --reporter spec --colors --slow 10000"
    },
    "bin": {
        "node-transmission": "./bin/node-transmission"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/FLYBYME/node-transmission.git"
    },
    "main": "lib/transmission",
    "devDependencies": {
        "async": "^0.9.0",
        "chai": "^1.9.2",
        "dotenv": "^0.4.0",
        "mocha": "^2.0.1",
        "mocha-jshint": "0.0.9",
        "progress": "^1.1.8"
    },
    "dependencies": {
        "async": "^2.1.4",
        "yargs": "^1.3.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
