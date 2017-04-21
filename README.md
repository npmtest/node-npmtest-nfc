# npmtest-nfc

#### basic test coverage for  nfc (v0.3.3)  [![npm package](https://img.shields.io/npm/v/npmtest-nfc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nfc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nfc.svg)](https://travis-ci.org/npmtest/node-npmtest-nfc)

#### Node NFC functionallity through libnfc

[![NPM](https://nodei.co/npm/nfc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nfc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nfc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nfc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nfc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nfc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nfc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nfc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nfc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nfc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nfc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nfc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nfc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nfc/build/test-report.html](https://npmtest.github.io/node-npmtest-nfc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nfc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nfc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nfc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nfc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nfc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nfc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nfc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nfc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nfc",
    "version": "0.3.3",
    "description": "Node NFC functionallity through libnfc",
    "main": "index.js",
    "scripts": {
        "test": "node test.js",
        "install": "node-gyp clean configure rebuild"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Camme/node-nfc.git"
    },
    "keywords": [
        "nfc"
    ],
    "dependencies": {
        "ndef": "0.1.2",
        "bindings": "1.2.1",
        "nan": "2.3.5",
        "node-gyp": "3.0.3"
    },
    "author": "Camilo Tapia <camilo.tapia@gmail.com>",
    "maintainers": [
        {
            "name": "Jeroen Vollenbrock",
            "url": "http://athom.nl"
        }
    ],
    "license": "MIT",
    "gypfile": true,
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
