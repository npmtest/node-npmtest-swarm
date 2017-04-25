# npmtest-swarm

#### basic test coverage for  [swarm (v0.3.25)](http://github.com/gritzko/swarm)  [![npm package](https://img.shields.io/npm/v/npmtest-swarm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swarm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swarm.svg)](https://travis-ci.org/npmtest/node-npmtest-swarm)

#### _reactive data sync lib: replicated model for your web app_

[![NPM](https://nodei.co/npm/swarm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swarm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swarm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swarm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swarm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swarm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swarm/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-swarm/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-swarm/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swarm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swarm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swarm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swarm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swarm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swarm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swarm/build/test-report.html](https://npmtest.github.io/node-npmtest-swarm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swarm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swarm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swarm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swarm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swarm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swarm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swarm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swarm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Victor Grishchenko"
    },
    "browser": "lib/Html5Client.js",
    "bugs": {
        "url": "https://github.com/gritzko/swarm/issues"
    },
    "contributors": [
        {
            "name": "Aleksei Balandin"
        },
        {
            "name": "Andrey Popp"
        }
    ],
    "dependencies": {
        "ws": "~0.4.31"
    },
    "description": "_reactive data sync lib: replicated model for your web app_",
    "devDependencies": {
        "browserify": "",
        "istanbul": "^0.3.2",
        "jshint": "",
        "leveldown": "1.0.0",
        "nopt": "",
        "qunit": "^0.7.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5d852f155406e1b9c1162e4a6db8e7c1fa46769e",
        "tarball": "https://registry.npmjs.org/swarm/-/swarm-0.3.25.tgz"
    },
    "email": "swarm.js@gmail.com",
    "files": [
        "lib/*.js",
        "dist/*.js",
        "Makefile",
        "LICENSE"
    ],
    "gitHead": "b945ea204aed653c762e8667e40a1047df2054c2",
    "homepage": "http://github.com/gritzko/swarm",
    "license": "MIT",
    "main": "lib/NodeServer.js",
    "maintainers": [
        {
            "name": "gritzko"
        },
        {
            "name": "abalandin"
        }
    ],
    "name": "swarm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gritzko/swarm.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "0.3.25",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
