# npmtest-iced-coffee-script

#### basic test coverage for  [iced-coffee-script (v108.0.11)](http://maxtaco.github.io/coffee-script)  [![npm package](https://img.shields.io/npm/v/npmtest-iced-coffee-script.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-iced-coffee-script) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-iced-coffee-script.svg)](https://travis-ci.org/npmtest/node-npmtest-iced-coffee-script)

#### IcedCoffeeScript

[![NPM](https://nodei.co/npm/iced-coffee-script.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/iced-coffee-script)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-iced-coffee-script/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-iced-coffee-script/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-iced-coffee-script/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-iced-coffee-script/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-iced-coffee-script/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-iced-coffee-script/build/test-report.html](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-iced-coffee-script/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-iced-coffee-script/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-iced-coffee-script/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-iced-coffee-script/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-iced-coffee-script/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Ashkenas + Maxwell Krohn"
    },
    "bin": {
        "iced": "./bin/coffee",
        "icake": "./bin/cake"
    },
    "bugs": {
        "url": "https://github.com/maxtaco/coffee-script/issues"
    },
    "dependencies": {
        "iced-runtime": ">=0.0.1"
    },
    "description": "IcedCoffeeScript",
    "devDependencies": {
        "browserify": "^4.1.8",
        "docco": "~0.6.2",
        "highlight.js": "~8.0.0",
        "jison": ">=0.2.0 <=0.4.13",
        "uglify-js": "~2.2",
        "underscore": "~1.5.2"
    },
    "directories": {
        "lib": "./lib/coffee-script"
    },
    "dist": {
        "shasum": "1d71ff93c9049728a6468385aa9bc891fd74c58f",
        "tarball": "https://registry.npmjs.org/iced-coffee-script/-/iced-coffee-script-108.0.11.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "28fea9408c890e3b7cc67d91948836bbaae8dbff",
    "homepage": "http://maxtaco.github.io/coffee-script",
    "keywords": [
        "javascript",
        "language",
        "coffeescript",
        "compiler"
    ],
    "license": "MIT",
    "main": "./lib/coffee-script/coffee-script",
    "maintainers": [
        {
            "name": "maxtaco"
        }
    ],
    "name": "iced-coffee-script",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/maxtaco/coffee-script.git"
    },
    "scripts": {
        "test": "node ./bin/cake test",
        "test-harmony": "node --harmony ./bin/cake test"
    },
    "version": "108.0.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
