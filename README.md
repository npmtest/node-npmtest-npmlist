# npmtest-npmlist

#### test coverage for  [npmlist (v3.1.2)](https://github.com/geekjuice/npmlist)  [![npm package](https://img.shields.io/npm/v/npmtest-npmlist.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npmlist) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npmlist.svg)](https://travis-ci.org/npmtest/node-npmtest-npmlist)

#### Pretty npm list

[![NPM](https://nodei.co/npm/npmlist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npmlist)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npmlist/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npmlist/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npmlist/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npmlist/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npmlist/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npmlist/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npmlist/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npmlist/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npmlist/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npmlist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npmlist/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npmlist/build/test-report.html](https://npmtest.github.io/node-npmtest-npmlist/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npmlist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npmlist/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npmlist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npmlist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npmlist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npmlist/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npmlist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npmlist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicholas Hwang"
    },
    "bin": {
        "npmlist": "./bin/npmlist"
    },
    "bugs": {
        "url": "https://github.com/geekjuice/npmlist/issues"
    },
    "dependencies": {
        "chalk": "^1.0.0"
    },
    "description": "Pretty npm list",
    "devDependencies": {
        "chai": "^3.0.0",
        "del": "^1.2.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.1.0",
        "gulp-bump": "^0.3.1",
        "gulp-filter": "^2.0.2",
        "gulp-plumber": "^1.0.1",
        "gulp-tag-version": "^1.2.1",
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "bcc2e29ee9e3644d295f49c4cd1c0b0abdf41edf",
        "tarball": "https://registry.npmjs.org/npmlist/-/npmlist-3.1.2.tgz"
    },
    "gitHead": "30fcd6daf26e44fd5e88b290bd287316d2289619",
    "homepage": "https://github.com/geekjuice/npmlist",
    "license": "MIT",
    "maintainers": [
        {
            "name": "geekjuice"
        }
    ],
    "name": "npmlist",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/geekjuice/npmlist.git"
    },
    "scripts": {
        "build": "gulp build",
        "start": "./bin/npmlist",
        "watch": "gulp watch"
    },
    "version": "3.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
