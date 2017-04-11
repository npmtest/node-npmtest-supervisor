# test coverage for  [supervisor (v0.12.0)](https://github.com/petruisfan/node-supervisor/)  [![npm package](https://img.shields.io/npm/v/npmtest-supervisor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-supervisor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-supervisor.svg)](https://travis-ci.org/npmtest/node-npmtest-supervisor)
#### A supervisor program for running nodejs programs

[![NPM](https://nodei.co/npm/supervisor.png?downloads=true)](https://www.npmjs.com/package/supervisor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-supervisor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-supervisor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-supervisor/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-supervisor/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-supervisor%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-supervisor/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-supervisor/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-supervisor%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-supervisor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-supervisor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "email": "i@izs.me"
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
            "name": "Todd Branchflower",
            "email": "toddbran@stanford.edu"
        },
        {
            "name": "Giannis Dzegoutanis",
            "email": "erasmospunk@gmail.com"
        },
        {
            "name": "Brian Ehmann",
            "email": "behmann@gmail.com"
        },
        {
            "name": "Corey Jewett",
            "email": "cj@syntheticplayground.com"
        },
        {
            "name": "Taka Kojima",
            "email": "taka.kojima@ff0000.com"
        },
        {
            "name": "Aneil Mallavarapu",
            "email": "aneil@blipboard.com"
        },
        {
            "name": "Doug McCall",
            "email": "dhm116@psu.edu"
        },
        {
            "name": "Mathieu M-Gosselin",
            "email": "mathieumg@gmail.com"
        },
        {
            "name": "David Murdoch",
            "email": "hello@davidmurdoch.com"
        },
        {
            "name": "mx1700",
            "email": "mx1700@gmail.com"
        },
        {
            "name": "Michiel ter Reehorst",
            "email": "jm.ter.reehorst@jamiter.com"
        },
        {
            "name": "Jonathan 'Wolf' Rentzsch",
            "email": "jwr.git@redshed.net"
        },
        {
            "name": "John Roberts",
            "email": "jroberts@logitech.com"
        },
        {
            "name": "Scott Sanders",
            "email": "scott@stonecobra.com"
        },
        {
            "name": "Thomas Schaaf",
            "email": "schaaf@komola.de"
        },
        {
            "name": "Fernando H. Silva",
            "email": "ferhensil@gmail.com"
        },
        {
            "name": "Kei Son",
            "email": "heyacct@gmail.com"
        },
        {
            "name": "David Taylor",
            "email": "david@zensatellite.com"
        },
        {
            "name": "Antonio Touriño",
            "email": "atourino@gmail.com"
        },
        {
            "name": "Oliver Wong",
            "email": "oliver@owiber.com"
        },
        {
            "name": "Di Wu",
            "email": "dw323@cornell.edu"
        },
        {
            "name": "Jesse Yang",
            "email": "jyyjcc@gmail.com"
        },
        {
            "name": "Ian Young",
            "email": "ian.greenleaf@gmail.com"
        },
        {
            "name": "jazzzz",
            "email": "jazzzz@gmail.com"
        },
        {
            "name": "philpill",
            "email": "github@philpill.net"
        },
        {
            "name": "rma4ok",
            "email": "rma4ok@gmail.com"
        },
        {
            "name": "Petru Isfan",
            "email": "petru.isfan@gmail.com"
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
            "name": "iangreenleaf",
            "email": "ian.greenleaf@gmail.com"
        },
        {
            "name": "isaacs",
            "email": "isaacs@npmjs.com"
        },
        {
            "name": "petruisfan",
            "email": "petru.isfan@gmail.com"
        }
    ],
    "name": "supervisor",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
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
