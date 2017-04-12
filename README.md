# test coverage for  [parse (v1.9.2)](https://www.parse.com)  [![npm package](https://img.shields.io/npm/v/npmtest-parse.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parse) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parse.svg)](https://travis-ci.org/npmtest/node-npmtest-parse)
#### The Parse JavaScript SDK

[![NPM](https://nodei.co/npm/parse.png?downloads=true)](https://www.npmjs.com/package/parse)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parse/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parse/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parse/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parse/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parse/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parse/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parse/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parse/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-parse/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-parse/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-parse%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parse/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parse/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-parse%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parse/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "react-native": false
    },
    "bugs": {
        "url": "https://github.com/ParsePlatform/Parse-SDK-JS/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "ws": "^1.0.1",
        "xmlhttprequest": "^1.7.0"
    },
    "description": "The Parse JavaScript SDK",
    "devDependencies": {
        "babel-jest": "^15.0.0",
        "babel-plugin-flow-comments": "^1.0.9",
        "babel-plugin-inline-package-json": "~2.0.0",
        "babel-plugin-minify-dead-code-elimination": "0.0.2",
        "babel-plugin-transform-inline-environment-variables": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-2": "^6.13.0",
        "browserify": "^11.0.1",
        "codecov.io": "^0.1.6",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.2",
        "gulp-derequire": "^2.1.0",
        "gulp-insert": "^0.5.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-uglify": "^1.4.0",
        "jasmine-reporters": "~1.0.0",
        "jest-cli": "^15.1.1",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e41d7cb6efd464eea30c34ec0651548f66c5b8e4",
        "tarball": "https://registry.npmjs.org/parse/-/parse-1.9.2.tgz"
    },
    "files": [
        "index.js",
        "node.js",
        "react-native.js",
        "dist/",
        "lib/",
        "LICENSE",
        "PATENTS",
        "README.md"
    ],
    "gitHead": "b01f2df856121dd557bc7e936e4ca32a4682b269",
    "homepage": "https://www.parse.com",
    "jest": {
        "automock": true,
        "collectCoverage": true,
        "testPathDirs": [
            "src/"
        ],
        "testPathIgnorePatterns": [
            "/node_modules/",
            "/test_helpers/"
        ],
        "scriptPreprocessor": "babel-jest.js",
        "setupTestFrameworkScriptFile": "setup-jest.js"
    },
    "keywords": [
        "cloud",
        "mobile",
        "api"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "andrewimm",
            "email": "andrewi@fb.com"
        },
        {
            "name": "grantland",
            "email": "grantlandchew@gmail.com"
        },
        {
            "name": "lacker",
            "email": "lacker@gmail.com"
        },
        {
            "name": "nlutsenko",
            "email": "nlutsenko@me.com"
        },
        {
            "name": "peterdotjs",
            "email": "pdotjs@gmail.com"
        },
        {
            "name": "wangmengyan95",
            "email": "wangmengyan95@gmail.com"
        }
    ],
    "name": "parse",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ParsePlatform/Parse-SDK-JS.git"
    },
    "scripts": {
        "build": "./build_releases.sh",
        "release": "./build_releases.sh && npm publish",
        "test": "PARSE_BUILD=node jest"
    },
    "version": "1.9.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
