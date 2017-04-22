# npmtest-cost-of-modules

#### basic test coverage for  [cost-of-modules (v1.0.1)](https://github.com/siddharthkp/cost-of-modules#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cost-of-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cost-of-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cost-of-modules.svg)](https://travis-ci.org/npmtest/node-npmtest-cost-of-modules)

#### Find out which of your dependencies are slowing you down 🐢

[![NPM](https://nodei.co/npm/cost-of-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cost-of-modules)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cost-of-modules/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cost-of-modules/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cost-of-modules/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cost-of-modules/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cost-of-modules/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cost-of-modules/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cost-of-modules/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cost-of-modules/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cost-of-modules/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cost-of-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cost-of-modules/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cost-of-modules/build/test-report.html](https://npmtest.github.io/node-npmtest-cost-of-modules/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cost-of-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cost-of-modules/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cost-of-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cost-of-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cost-of-modules",
    "version": "1.0.1",
    "description": "Find out which of your dependencies are slowing you down 🐢",
    "author": "siddharthkp",
    "homepage": "https://github.com/siddharthkp/cost-of-modules#readme",
    "main": "src/index.js",
    "bin": "lib/index.js",
    "scripts": {
        "build": "babel src -d lib && babel test/src -d test/lib",
        "lint": "eslint src",
        "test": "npm run lint && npm run build && npm run ava",
        "ava": "ava test/lib/*.js -s --no-cache"
    },
    "files": [
        "lib"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/siddharthkp/cost-of-modules.git"
    },
    "engines": {
        "node": ">= 5.0.0",
        "npm": ">= 3.0.0"
    },
    "keywords": "cost, modules, bloat",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/siddharthkp/cost-of-modules/issues"
    },
    "dependencies": {
        "ansi-regex": "2.0.0",
        "cli-table2": "0.2.0",
        "colors": "1.1.2",
        "fs-extra": "2.1.0",
        "sync-exec": "0.6.2",
        "yargs-parser": "4.0.2"
    },
    "devDependencies": {
        "ava": "0.16.0",
        "babel-cli": "6.18.0",
        "babel-preset-es2015": "6.18.0",
        "eslint": "3.8.1",
        "eslint-config-airbnb": "12.0.0",
        "eslint-plugin-import": "1.16.0",
        "eslint-plugin-jsx-a11y": "2.2.3",
        "eslint-plugin-react": "6.4.1"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
