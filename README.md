# npmtest-gulp-batch

#### basic test coverage for  [gulp-batch (v1.0.5)](https://github.com/floatdrop/gulp-batch)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-batch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-batch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-batch.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-batch)

#### Event batcher for gulp-watcher

[![NPM](https://nodei.co/npm/gulp-batch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-batch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-batch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-batch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-batch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-batch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-batch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-batch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-batch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-batch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-batch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-batch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-batch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-batch/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-batch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-batch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-batch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-batch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-batch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-batch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-batch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vsevolod Strukchinsky"
    },
    "bugs": {
        "url": "https://github.com/floatdrop/gulp-batch/issues"
    },
    "dependencies": {
        "async-done": "^1.0.0",
        "stream-array": "^1.0.1"
    },
    "description": "Event batcher for gulp-watcher",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.5",
        "mocha": "^2.0.1",
        "mocha-lcov-reporter": "0.0.1",
        "should": "^4.3.1",
        "stream-assert": "^2.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c40fc9b2303674897b1216d82e1518b73217da59",
        "tarball": "https://registry.npmjs.org/gulp-batch/-/gulp-batch-1.0.5.tgz"
    },
    "gitHead": "dba7f073deb4a0865d02be289faf350ad5723945",
    "homepage": "https://github.com/floatdrop/gulp-batch",
    "keywords": [
        "gulp",
        "batch",
        "throttle",
        "debounce",
        "gulpfriendly",
        "watch",
        "mocha"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "floatdrop"
        }
    ],
    "name": "gulp-batch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/floatdrop/gulp-batch.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul cover _mocha -- test/*.js --reporter spec"
    },
    "version": "1.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
