# npmtest-generator-mobile

#### basic test coverage for  [generator-mobile (v2.0.0-alpha)](https://github.com/yeoman/generator-mobile)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-mobile.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-mobile) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-mobile.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-mobile)

#### Yeoman generator for mobile based on Web Starter Kit

[![NPM](https://nodei.co/npm/generator-mobile.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-mobile)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-mobile/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-mobile/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-mobile/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-mobile/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-mobile/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-mobile/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-mobile/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-mobile/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-mobile/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-mobile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-mobile/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-mobile/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-mobile/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-mobile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-mobile/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-mobile/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-mobile/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-mobile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-mobile/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-mobile/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-mobile/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-mobile",
    "version": "2.0.0-alpha",
    "description": "Yeoman generator for mobile based on Web Starter Kit",
    "homepage": "https://github.com/yeoman/generator-mobile",
    "bugs": "https://github.com/yeoman/generator-mobile/issues",
    "license": "BSD",
    "main": "app/index.js",
    "repository": "yeoman/generator-mobile",
    "author": "Chrome Developer Relations",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "files": [
        "app"
    ],
    "keywords": [
        "yeoman-generator",
        "web",
        "app",
        "front-end",
        "mobile",
        "wsk",
        "web-starter-kit"
    ],
    "dependencies": {
        "yeoman-generator": "^0.17.0",
        "chalk": "^0.5.0",
        "yosay": "^0.3.0",
        "download": "^3.1.1",
        "request": "^2.46.0",
        "iniparser": "^1.0.5"
    },
    "devDependencies": {
        "mocha": "*",
        "nock": "^0.48.2"
    },
    "peerDependencies": {
        "yo": ">=1.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
