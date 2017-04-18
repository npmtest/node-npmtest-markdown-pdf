# npmtest-markdown-pdf

#### test coverage for  [markdown-pdf (v7.0.0)](https://github.com/alanshaw/markdown-pdf)  [![npm package](https://img.shields.io/npm/v/npmtest-markdown-pdf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-markdown-pdf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-markdown-pdf.svg)](https://travis-ci.org/npmtest/node-npmtest-markdown-pdf)

#### Markdown to PDF converter

[![NPM](https://nodei.co/npm/markdown-pdf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/markdown-pdf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-markdown-pdf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-markdown-pdf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-markdown-pdf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-markdown-pdf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-markdown-pdf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-markdown-pdf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-markdown-pdf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-markdown-pdf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-markdown-pdf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-markdown-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-markdown-pdf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-markdown-pdf/build/test-report.html](https://npmtest.github.io/node-npmtest-markdown-pdf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-markdown-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-markdown-pdf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-markdown-pdf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-markdown-pdf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-markdown-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-markdown-pdf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-markdown-pdf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-markdown-pdf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alan Shaw"
    },
    "bin": {
        "markdown-pdf": "bin/markdown-pdf"
    },
    "bugs": {
        "url": "https://github.com/alanshaw/markdown-pdf/issues"
    },
    "dependencies": {
        "commander": "^2.2.0",
        "duplexer": "^0.1.1",
        "extend": "^3.0.0",
        "highlight.js": "^9.1.0",
        "phantomjs-prebuilt": "^2.1.3",
        "remarkable": "^1.6.0",
        "stream-from-to": "^1.4.2",
        "through2": "^2.0.0",
        "tmp": "0.0.28"
    },
    "description": "Markdown to PDF converter",
    "devDependencies": {
        "coveralls": "^2.10.0",
        "istanbul": "^0.4.0",
        "pdf-text": "^0.4.0",
        "standard": "^5.4.1",
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "3c70e09a6ef3dae2c5059b3a2294bd6581d269ce",
        "tarball": "https://registry.npmjs.org/markdown-pdf/-/markdown-pdf-7.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "62a12b3de8f70ac04e92eed11bb380ae7a37bdf2",
    "homepage": "https://github.com/alanshaw/markdown-pdf",
    "keywords": [
        "markdown",
        "pdf",
        "convert",
        "template"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "alanshaw"
        }
    ],
    "name": "markdown-pdf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/alanshaw/markdown-pdf.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "test": "standard && istanbul cover node_modules/.bin/tape test/*.js"
    },
    "standard": {
        "ignore": [
            "html5bp/**"
        ]
    },
    "version": "7.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
