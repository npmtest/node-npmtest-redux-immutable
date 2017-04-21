# npmtest-redux-immutable

#### basic test coverage for  [redux-immutable (v4.0.0)](https://github.com/gajus/redux-immutable#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-immutable.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-immutable) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-immutable.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-immutable)

#### redux-immutable is used to create an equivalent function of Redux combineReducers that works with Immutable.js state.

[![NPM](https://nodei.co/npm/redux-immutable.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-immutable)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-immutable/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-immutable/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-immutable/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-immutable/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-immutable/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-immutable/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-immutable/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-immutable/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-immutable/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-immutable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-immutable/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-immutable/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-immutable/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-immutable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-immutable/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-immutable/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-immutable/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-immutable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-immutable/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-immutable/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-immutable/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gajus Kuizinas",
        "url": "http://gajus.com"
    },
    "bugs": {
        "url": "https://github.com/gajus/redux-immutable/issues"
    },
    "dependencies": {},
    "description": "redux-immutable is used to create an equivalent function of Redux combineReducers that works with Immutable.js state.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-flow-runtime": "0.0.6",
        "babel-plugin-syntax-flow": "^6.18.0",
        "babel-plugin-transform-flow-strip-types": "^6.21.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "benchmark": "^2.1.3",
        "chai": "^3.5.0",
        "eslint": "^3.13.1",
        "eslint-config-canonical": "^6.0.0",
        "flow-runtime": "0.0.6",
        "husky": "^0.12.0",
        "immutable": "^3.8.1 || ^4.0.0-rc.1",
        "mocha": "^3.2.0",
        "semantic-release": "^6.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "3a1a32df66366462b63691f0e1dc35e472bbc9f3",
        "tarball": "https://registry.npmjs.org/redux-immutable/-/redux-immutable-4.0.0.tgz"
    },
    "gitHead": "db26f25e70bef74dbd10c39c008ad507f9d7ce7e",
    "homepage": "https://github.com/gajus/redux-immutable#readme",
    "keywords": [
        "immutable",
        "redux"
    ],
    "license": "BSD-3-Clause",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "gajus"
        }
    ],
    "name": "redux-immutable",
    "optionalDependencies": {},
    "peerDependencies": {
        "immutable": "^3.8.1 || ^4.0.0-rc.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gajus/redux-immutable.git"
    },
    "scripts": {
        "benchmark": "NODE_ENV=production node ./benchmarks/index.js",
        "build": "babel ./src --source-maps --out-dir ./dist",
        "lint": "eslint ./src ./tests",
        "precommit": "npm run lint && npm run test",
        "test": "mocha --compilers js:babel-register './tests/**/*.js'"
    },
    "version": "4.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
