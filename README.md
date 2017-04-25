# npmtest-supervisor

#### basic test coverage for  [supervisor (v0.12.0)](https://github.com/petruisfan/node-supervisor/)  [![npm package](https://img.shields.io/npm/v/npmtest-supervisor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-supervisor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-supervisor.svg)](https://travis-ci.org/npmtest/node-npmtest-supervisor)

#### A supervisor program for running nodejs programs

[![NPM](https://nodei.co/npm/supervisor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/supervisor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-supervisor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-supervisor/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-supervisor/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-supervisor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-supervisor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-supervisor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-supervisor/build/test-report.html](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-supervisor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-supervisor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-supervisor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-supervisor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter"
    },
    "bin": {
        "node-supervisor": "lib/cli-wrapper.js",
        "supervisor": "lib/cli-wrapper.js"
    },
    "bugs": {
        "url": "https://github.com/petruisfan/node-supervisor/issues"
    },
    "contributors": [
        {
            "name": "Todd Branchflower"
        },
        {
            "name": "Giannis Dzegoutanis"
        },
        {
            "name": "Brian Ehmann"
        },
        {
            "name": "Corey Jewett"
        },
        {
            "name": "Taka Kojima"
        },
        {
            "name": "Aneil Mallavarapu"
        },
        {
            "name": "Doug McCall"
        },
        {
            "name": "Mathieu M-Gosselin"
        },
        {
            "name": "David Murdoch"
        },
        {
            "name": "mx1700"
        },
        {
            "name": "Michiel ter Reehorst"
        },
        {
            "name": "Jonathan 'Wolf' Rentzsch"
        },
        {
            "name": "John Roberts"
        },
        {
            "name": "Scott Sanders"
        },
        {
            "name": "Thomas Schaaf"
        },
        {
            "name": "Fernando H. Silva"
        },
        {
            "name": "Kei Son"
        },
        {
            "name": "David Taylor"
        },
        {
            "name": "Antonio Touriño"
        },
        {
            "name": "Oliver Wong"
        },
        {
            "name": "Di Wu"
        },
        {
            "name": "Jesse Yang"
        },
        {
            "name": "Ian Young"
        },
        {
            "name": "jazzzz"
        },
        {
            "name": "philpill"
        },
        {
            "name": "rma4ok"
        },
        {
            "name": "Petru Isfan"
        }
    ],
    "dependencies": {},
    "description": "A supervisor program for running nodejs programs",
    "devDependencies": {
        "nodeunit": "~0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "de7e6337015b291851c10f3538c4a7f04917ecc1",
        "tarball": "https://registry.npmjs.org/supervisor/-/supervisor-0.12.0.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "gitHead": "85d92db02a651d8523f1a787a5c474668afb97b3",
    "homepage": "https://github.com/petruisfan/node-supervisor/",
    "license": "MIT",
    "main": "lib/supervisor.js",
    "maintainers": [
        {
            "name": "iangreenleaf"
        },
        {
            "name": "isaacs"
        },
        {
            "name": "petruisfan"
        }
    ],
    "name": "supervisor",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/petruisfan/node-supervisor.git"
    },
    "scripts": {
        "test": "./node_modules/nodeunit/bin/nodeunit test/*.test.js"
    },
    "version": "0.12.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
