# npmtest-jasmine-expect

#### basic test coverage for  [jasmine-expect (v3.7.0)](https://github.com/JamieMason/Jasmine-Matchers)  [![npm package](https://img.shields.io/npm/v/npmtest-jasmine-expect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jasmine-expect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jasmine-expect.svg)](https://travis-ci.org/npmtest/node-npmtest-jasmine-expect)

#### Additional matchers for the Jasmine BDD JavaScript testing library

[![NPM](https://nodei.co/npm/jasmine-expect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jasmine-expect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jasmine-expect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jasmine-expect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jasmine-expect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jasmine-expect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jasmine-expect/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jasmine-expect/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jasmine-expect/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jasmine-expect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jasmine-expect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jasmine-expect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jasmine-expect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jasmine-expect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jasmine-expect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jasmine-expect/build/test-report.html](https://npmtest.github.io/node-npmtest-jasmine-expect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jasmine-expect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jasmine-expect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jasmine-expect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jasmine-expect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jasmine-expect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jasmine-expect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jasmine-expect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jasmine-expect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jamie Mason",
        "url": "https://github.com/JamieMason"
    },
    "bugs": {
        "url": "https://github.com/JamieMason/Jasmine-Matchers/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Ariel Mashraki",
            "url": "https://github.com/a8m"
        },
        {
            "name": "Caleb Jares",
            "url": "https://github.com/cable729"
        },
        {
            "name": "David Parker",
            "url": "https://github.com/boldfacedesign"
        },
        {
            "name": "David Tanner",
            "url": "https://github.com/DavidTanner"
        },
        {
            "name": "Elior Boukhobza",
            "url": "https://github.com/mallowigi"
        },
        {
            "name": "ik9999",
            "url": "https://github.com/ik9999"
        },
        {
            "name": "Jacob Ward"
        },
        {
            "name": "Jamie Mason",
            "url": "https://github.com/JamieMason"
        },
        {
            "name": "Jarek Rencz",
            "url": "https://github.com/jrencz"
        },
        {
            "name": "Jose M Andres",
            "url": "https://github.com/jmandreslopez"
        },
        {
            "name": "Klaus Sevensleeper",
            "url": "https://github.com/k7sleeper"
        },
        {
            "name": "Marcin Wosinek",
            "url": "https://github.com/marcin-wosinek"
        },
        {
            "name": "Mathieu Robin",
            "url": "https://github.com/MathRobin"
        },
        {
            "name": "Sam L'ecuyer",
            "url": "https://github.com/samlecuyer"
        },
        {
            "name": "Vilmos Ioo",
            "url": "https://github.com/vilmosioo"
        }
    ],
    "dependencies": {
        "add-matchers": "0.5.0"
    },
    "description": "Additional matchers for the Jasmine BDD JavaScript testing library",
    "devDependencies": {
        "babel-preset-env": "1.2.1",
        "babelify": "7.3.0",
        "browserify": "14.1.0",
        "codeclimate-test-reporter": "0.4.1",
        "cz-conventional-changelog": "2.0.0",
        "gulp": "3.9.1",
        "husky": "0.13.2",
        "jasmine-core": "2.5.2",
        "jest": "19.0.2",
        "karma": "1.5.0",
        "karma-browserstack-launcher": "1.2.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-cli": "1.0.1",
        "karma-coverage": "1.1.1",
        "karma-firefox-launcher": "1.0.1",
        "karma-jasmine": "1.1.0",
        "karma-nested-reporter": "0.1.5",
        "saucelabs": "1.4.0",
        "validate-commit-msg": "2.11.2",
        "vinyl-source-stream": "1.1.0",
        "xo": "0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "841e1382f4bff0258c8dc96eca27c4fbc6ae4887",
        "tarball": "https://registry.npmjs.org/jasmine-expect/-/jasmine-expect-3.7.0.tgz"
    },
    "gitHead": "ad935bc725682db9c6fdb841f11acc94badcc2f3",
    "homepage": "https://github.com/JamieMason/Jasmine-Matchers",
    "jest": {
        "setupTestFrameworkScriptFile": "<rootDir>/index.js",
        "roots": [
            "<rootDir>/test"
        ]
    },
    "keywords": [
        "BDD",
        "TDD",
        "jasmine",
        "testing"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fold_left"
        }
    ],
    "name": "jasmine-expect",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/JamieMason/Jasmine-Matchers.git"
    },
    "scripts": {
        "browserstack-android": "karma start karma/browserstack-android.conf.js",
        "browserstack-chrome": "karma start karma/browserstack-chrome.conf.js",
        "browserstack-firefox": "karma start karma/browserstack-firefox.conf.js",
        "browserstack-ie": "karma start karma/browserstack-ie.conf.js",
        "browserstack-ios": "karma start karma/browserstack-ios.conf.js",
        "browserstack-opera": "karma start karma/browserstack-opera.conf.js",
        "browserstack-safari": "karma start karma/browserstack-safari.conf.js",
        "build": "gulp browserify",
        "commitmsg": "validate-commit-msg",
        "lint": "xo --fix",
        "test": "npm run lint && npm run browserstack-android && npm run browserstack-ios && npm run browserstack-ie && npm run browserstack-safari && npm run browserstack-opera && npm run browserstack-firefox && npm run browserstack-chrome",
        "test:jest": "jest",
        "test:local": "karma start karma/base.conf.js --browsers Chrome",
        "watch": "gulp watch"
    },
    "version": "3.7.0",
    "xo": {
        "envs": [
            "jasmine",
            "node"
        ],
        "esnext": true,
        "globals": [
            "any"
        ],
        "overrides": [
            {
                "files": "examples/**/*.js",
                "esnext": false
            },
            {
                "files": "examples/karma/**/*.js",
                "envs": [
                    "browser",
                    "jasmine"
                ]
            },
            {
                "files": "examples/protractor/**/*.js",
                "envs": [
                    "protractor",
                    "jasmine"
                ]
            }
        ],
        "rules": {
            "func-names": 0,
            "max-nested-callbacks": 0,
            "no-array-constructor": 0,
            "no-new-object": 0,
            "no-new-wrappers": 0,
            "unicorn/filename-case": 0
        },
        "space": 2
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
