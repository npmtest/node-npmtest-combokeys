# test coverage for  [combokeys (v2.4.6)](https://github.com/PolicyStat/combokeys)  [![npm package](https://img.shields.io/npm/v/npmtest-combokeys.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-combokeys) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-combokeys.svg)](https://travis-ci.org/npmtest/node-npmtest-combokeys)
#### Handles keyboard shortcuts in the browser

[![NPM](https://nodei.co/npm/combokeys.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/combokeys)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-combokeys/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-combokeys/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-combokeys/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-combokeys/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-combokeys/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-combokeys/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-combokeys/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-combokeys/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-combokeys/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-combokeys/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-combokeys/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-combokeys/build/test-report.html](https://npmtest.github.io/node-npmtest-combokeys/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-combokeys/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-combokeys/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-combokeys/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-combokeys/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-combokeys/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-combokeys/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-combokeys/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-combokeys/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/PolicyStat/combokeys/issues"
    },
    "contributors": [
        {
            "name": "Shahar Or",
            "url": "https://github.com/mightyiam"
        },
        {
            "name": "Craig Campbell",
            "url": "http://craig.is"
        }
    ],
    "dependencies": {},
    "description": "Handles keyboard shortcuts in the browser",
    "devDependencies": {
        "browserify": "^9.0.3",
        "es5-shim": "^4.0.3",
        "mocha": "^2.0.1",
        "phantomjs": "^1.9.12",
        "proclaim": "^3.1.0",
        "sinon": "^1.12.1",
        "standard": "*",
        "zuul": "^2.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a5c47599632af7a36d1d9c2f98518c95b253d83b",
        "tarball": "https://registry.npmjs.org/combokeys/-/combokeys-2.4.6.tgz"
    },
    "gitHead": "5d46174289adc9171652520a8a3d0c0f83ea7183",
    "homepage": "https://github.com/PolicyStat/combokeys",
    "implements": [
        "CommonJS/Modules/1.0"
    ],
    "keywords": [
        "keyboard",
        "shortcuts",
        "events",
        "browser"
    ],
    "license": {
        "type": "Apache 2.0",
        "url": "https://www.apache.org/licenses/LICENSE-2.0.txt"
    },
    "main": "Combokeys/index.js",
    "maintainers": [
        {
            "name": "mightyiam"
        },
        {
            "name": "weswinham"
        }
    ],
    "name": "combokeys",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/PolicyStat/combokeys.git"
    },
    "scripts": {
        "build": "mkdir -p dist && browserify . -o dist/combokeys.js --standalone Combokeys",
        "lint": "standard",
        "test": "npm run lint && npm run unit && npm run build",
        "unit": "./node_modules/zuul/bin/zuul --phantom -- test"
    },
    "standard": {
        "ignore": [
            "dist/**"
        ]
    },
    "version": "2.4.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
