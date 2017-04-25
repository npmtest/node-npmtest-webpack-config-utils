# npmtest-webpack-config-utils

#### basic test coverage for  [webpack-config-utils (v2.3.0)](https://github.com/kentcdodds/webpack-config-utils#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-config-utils.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-config-utils) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-config-utils.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-config-utils)

#### Utilities to help your webpack config be easier to read

[![NPM](https://nodei.co/npm/webpack-config-utils.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-config-utils)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-config-utils/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-webpack-config-utils/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-config-utils/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-config-utils/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-config-utils/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-config-utils/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-config-utils/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-config-utils/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-config-utils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-config-utils/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-config-utils/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kent C. Dodds",
        "url": "http://kentcdodds.com/"
    },
    "bugs": {
        "url": "https://github.com/kentcdodds/webpack-config-utils/issues"
    },
    "bundleDependencies": [
        "webpack-combine-loaders"
    ],
    "config": {
        "ghooks": {
            "commit-msg": "opt --in commit-msg --exec \"validate-commit-msg\"",
            "pre-commit": "opt --in pre-commit --exec \"npm start validate\""
        },
        "commitizen": {
            "path": "node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "webpack-combine-loaders": "2.0.0"
    },
    "description": "Utilities to help your webpack config be easier to read",
    "devDependencies": {
        "all-contributors-cli": "^3.0.0",
        "ava": "^0.15.2",
        "babel-cli": "^6.7.7",
        "babel-plugin-istanbul": "^1.0.3",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-stage-2": "^6.5.0",
        "babel-register": "^6.7.2",
        "codecov": "^1.0.1",
        "commitizen": "^2.8.1",
        "condition-node-version": "^1.3.0",
        "cross-env": "^2.0.0",
        "cz-conventional-changelog": "^1.1.6",
        "eslint": "^3.1.1",
        "eslint-config-kentcdodds": "^8.1.2",
        "ghooks": "^1.2.1",
        "lodash": "4.13.1",
        "nyc": "^7.0.0",
        "opt-cli": "^1.4.2",
        "p-s": "^1.0.4",
        "rimraf": "^2.5.2",
        "semantic-release": "^6.2.1",
        "validate-commit-msg": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "49aa66984a85a7c2c9991343137e8dd11b610afa",
        "tarball": "https://registry.npmjs.org/webpack-config-utils/-/webpack-config-utils-2.3.0.tgz"
    },
    "eslintConfig": {
        "extends": [
            "kentcdodds",
            "kentcdodds/ava"
        ],
        "rules": {
            "import/prefer-default-export": 0
        }
    },
    "files": [
        "dist"
    ],
    "gitHead": "10f3165ffe1e94a787cca62904d25d2e2efdec7d",
    "homepage": "https://github.com/kentcdodds/webpack-config-utils#readme",
    "keywords": [],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "kentcdodds"
        }
    ],
    "name": "webpack-config-utils",
    "nyc": {
        "all": true,
        "check-coverage": true,
        "branches": 100,
        "function": 100,
        "lines": 100,
        "statements": 100,
        "reporter": [
            "text",
            "lcov"
        ],
        "include": [
            "src"
        ],
        "sourceMap": false,
        "instrument": false,
        "require": [
            "babel-register"
        ]
    },
    "optionalDependencies": {},
    "release": {
        "verifyConditions": {
            "path": "condition-node-version",
            "node": "^6"
        }
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kentcdodds/webpack-config-utils.git"
    },
    "scripts": {
        "start": "package-scripts",
        "test": "package-scripts test"
    },
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
