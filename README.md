# test coverage for  [pretty-error (v2.1.0)](https://github.com/AriaMinaei/pretty-error#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pretty-error.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pretty-error) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pretty-error.svg)](https://travis-ci.org/npmtest/node-npmtest-pretty-error)
#### See nodejs errors with less clutter

[![NPM](https://nodei.co/npm/pretty-error.png?downloads=true)](https://www.npmjs.com/package/pretty-error)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pretty-error/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pretty-error/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pretty-error/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pretty-error/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pretty-error/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pretty-error/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pretty-error/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pretty-error/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-pretty-error/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-pretty-error/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-pretty-error%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pretty-error/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pretty-error/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-pretty-error%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pretty-error/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pretty-error/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pretty-error/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aria Minaei"
    },
    "bugs": {
        "url": "https://github.com/AriaMinaei/pretty-error/issues"
    },
    "dependencies": {
        "renderkid": "^2.0.1",
        "utila": "~0.4"
    },
    "description": "See nodejs errors with less clutter",
    "devDependencies": {
        "chai": "~1.9.2",
        "coffee-script": "~1.8.0",
        "jitter": "^1.3.0",
        "mocha": "~2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "87f4e9d706a24c87d6cbee9fabec001fcf8c75d8",
        "tarball": "https://registry.npmjs.org/pretty-error/-/pretty-error-2.1.0.tgz"
    },
    "gitHead": "26ae78383597b5184e46d120853171ee0ae138b4",
    "homepage": "https://github.com/AriaMinaei/pretty-error#readme",
    "keywords": [
        "pretty",
        "error",
        "exception",
        "debug",
        "error-handling",
        "readable",
        "colorful",
        "prettify",
        "format",
        "human"
    ],
    "license": "MIT",
    "main": "./lib/PrettyError.js",
    "maintainers": [
        {
            "name": "ariaminaei",
            "email": "aria.minaei@gmail.com"
        },
        {
            "name": "alexgorbatchev",
            "email": "alex.gorbatchev@gmail.com"
        }
    ],
    "name": "pretty-error",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/AriaMinaei/pretty-error.git"
    },
    "scripts": {
        "compile": "coffee --bare --compile --output ./lib ./src",
        "compile:watch": "jitter src lib -b",
        "prepublish": "npm run compile",
        "test": "mocha \"test/**/*.coffee\"",
        "test:watch": "mocha \"test/**/*.coffee\" --watch",
        "watch": "npm run compile:watch & npm run test:watch",
        "winwatch": "start/b npm run compile:watch & npm run test:watch"
    },
    "typings": "index.d.ts",
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
