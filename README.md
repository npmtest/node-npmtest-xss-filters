# npmtest-xss-filters

#### basic test coverage for  [xss-filters (v1.2.7)](https://github.com/yahoo/xss-filters)  [![npm package](https://img.shields.io/npm/v/npmtest-xss-filters.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xss-filters) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xss-filters.svg)](https://travis-ci.org/npmtest/node-npmtest-xss-filters)

#### Secure XSS Filters - Just sufficient output filtering to prevent XSS!

[![NPM](https://nodei.co/npm/xss-filters.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xss-filters)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xss-filters/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xss-filters/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xss-filters/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xss-filters/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xss-filters/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xss-filters/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xss-filters/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xss-filters/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xss-filters/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xss-filters/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xss-filters/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xss-filters/build/test-report.html](https://npmtest.github.io/node-npmtest-xss-filters/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xss-filters/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xss-filters/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xss-filters/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xss-filters/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xss-filters/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xss-filters/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xss-filters/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xss-filters/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "xss-filters",
    "version": "1.2.7",
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/yahoo/xss-filters/blob/master/LICENSE"
        }
    ],
    "description": "Secure XSS Filters - Just sufficient output filtering to prevent XSS!",
    "author": "Adonis Fung <adon@yahoo-inc.com>, Nera Liu <neraliu@gmail.com>,  and Albert Yu <yukinying@gmail.com>",
    "contributors": [
        {
            "name": "Adonis Fung"
        },
        {
            "name": "Nera Liu"
        },
        {
            "name": "Albert Yu"
        }
    ],
    "main": "src/xss-filters.js",
    "scripts": {
        "test": "grunt test",
        "hint": "grunt jshint",
        "docs": "grunt docs",
        "clean": "grunt clean",
        "build": "grunt"
    },
    "keywords": [
        "xss",
        "output filter",
        "sanitize",
        "sanitise",
        "escape",
        "encode",
        "filter",
        "context-aware",
        "context-sensitive",
        "security",
        "yahoo"
    ],
    "devDependencies": {
        "expect.js": "^0.3.1",
        "grunt": "^1.0.1",
        "grunt-browserify": "^5.0.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-jsdoc": "^2.1.0",
        "grunt-karma": "^2.0.0",
        "grunt-mocha-istanbul": "^5.0.2",
        "ink-docstrap": "^1.3.0",
        "istanbul": "^0.4.5",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-ie-launcher": "^1.0.0",
        "karma-mocha": "^1.1.1",
        "karma-sauce-launcher": "^1.0.0",
        "mocha": "^3.0.2"
    },
    "bugs": {
        "url": "https://github.com/yahoo/xss-filters/issues"
    },
    "homepage": "https://github.com/yahoo/xss-filters",
    "repository": {
        "type": "git",
        "url": "https://github.com/yahoo/xss-filters.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
