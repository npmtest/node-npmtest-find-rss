# npmtest-find-rss

#### basic test coverage for  find-rss (v1.6.4)  [![npm package](https://img.shields.io/npm/v/npmtest-find-rss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-find-rss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-find-rss.svg)](https://travis-ci.org/npmtest/node-npmtest-find-rss)

#### Find RSS/ATOM feed by HTML/URL

[![NPM](https://nodei.co/npm/find-rss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/find-rss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-find-rss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-find-rss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-find-rss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-find-rss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-find-rss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-find-rss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-find-rss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-find-rss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-find-rss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-find-rss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-find-rss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-find-rss/build/test-report.html](https://npmtest.github.io/node-npmtest-find-rss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-find-rss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-find-rss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-find-rss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-find-rss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-find-rss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-find-rss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-find-rss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-find-rss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "find-rss",
    "description": "Find RSS/ATOM feed by HTML/URL",
    "version": "1.6.4",
    "author": "nikezono",
    "dependencies": {
        "async": "^2.1.4",
        "feedparser": "^2.1.0",
        "htmlparser2": "^3.9.2",
        "iconv-lite": "^0.4.15",
        "jschardet": "^1.4.1",
        "request": "^2.79.0"
    },
    "devDependencies": {
        "codeclimate-test-reporter": "*",
        "coffee-errors": "*",
        "coffee-script": "*",
        "coffeelint": "^1.16.0",
        "grunt": "*",
        "grunt-coffeelint": "*",
        "grunt-contrib-clean": "*",
        "grunt-contrib-coffee": "*",
        "grunt-contrib-copy": "*",
        "grunt-contrib-watch": "*",
        "grunt-istanbul": "*",
        "grunt-mocha-test": "*",
        "grunt-notify": "*",
        "istanbul": "*",
        "mocha": "*",
        "nock": "^9.0.5",
        "underscore": "*"
    },
    "keywords": [
        "rss",
        "atom",
        "find",
        "feed"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/nikezono/node-find-rss"
    },
    "main": "lib/find-rss.js",
    "scripts": {
        "test": "grunt test",
        "prepublish": "grunt coffee"
    },
    "engines": {
        "node": "*"
    },
    "directories": {
        "test": "test"
    },
    "license": "BSD"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
