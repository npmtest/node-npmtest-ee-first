# npmtest-ee-first

#### basic test coverage for  ee-first (v1.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-ee-first.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ee-first) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ee-first.svg)](https://travis-ci.org/npmtest/node-npmtest-ee-first)

#### return the first event in a set of ee/event pairs

[![NPM](https://nodei.co/npm/ee-first.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ee-first)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ee-first/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ee-first/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ee-first/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ee-first/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ee-first/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ee-first/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ee-first/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ee-first/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ee-first/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ee-first/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ee-first/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ee-first/build/test-report.html](https://npmtest.github.io/node-npmtest-ee-first/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ee-first/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ee-first/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ee-first/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ee-first/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ee-first/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ee-first/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ee-first/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ee-first/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ee-first",
    "description": "return the first event in a set of ee/event pairs",
    "version": "1.1.1",
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com",
        "twitter": "https://twitter.com/jongleberry"
    },
    "contributors": [
        "Douglas Christopher Wilson <doug@somethingdoug.com>"
    ],
    "license": "MIT",
    "repository": "jonathanong/ee-first",
    "devDependencies": {
        "istanbul": "0.3.9",
        "mocha": "2.2.5"
    },
    "files": [
        "index.js",
        "LICENSE"
    ],
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
