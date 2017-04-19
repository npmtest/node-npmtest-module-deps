# npmtest-module-deps

#### test coverage for  [module-deps (v4.1.1)](https://github.com/substack/module-deps)  [![npm package](https://img.shields.io/npm/v/npmtest-module-deps.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-module-deps) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-module-deps.svg)](https://travis-ci.org/npmtest/node-npmtest-module-deps)

#### walk the dependency graph to generate json output that can be fed into browser-pack

[![NPM](https://nodei.co/npm/module-deps.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/module-deps)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-module-deps/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-module-deps/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-module-deps/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-module-deps/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-module-deps/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-module-deps/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-module-deps/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-module-deps/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-module-deps/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-module-deps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-module-deps/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-module-deps/build/test-report.html](https://npmtest.github.io/node-npmtest-module-deps/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-module-deps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-module-deps/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-module-deps/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-module-deps/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-module-deps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-module-deps/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-module-deps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-module-deps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "module-deps": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/module-deps/issues"
    },
    "dependencies": {
        "JSONStream": "^1.0.3",
        "browser-resolve": "^1.7.0",
        "cached-path-relative": "^1.0.0",
        "concat-stream": "~1.5.0",
        "defined": "^1.0.0",
        "detective": "^4.0.0",
        "duplexer2": "^0.1.2",
        "inherits": "^2.0.1",
        "parents": "^1.0.0",
        "readable-stream": "^2.0.2",
        "resolve": "^1.1.3",
        "stream-combiner2": "^1.1.1",
        "subarg": "^1.0.0",
        "through2": "^2.0.0",
        "xtend": "^4.0.0"
    },
    "description": "walk the dependency graph to generate json output that can be fed into browser-pack",
    "devDependencies": {
        "browser-pack": "^5.0.0",
        "tap": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "23215833f1da13fd606ccb8087b44852dcb821fd",
        "tarball": "https://registry.npmjs.org/module-deps/-/module-deps-4.1.1.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "gitHead": "4cce7975e909b91775411731a28e9d7e123e7079",
    "homepage": "https://github.com/substack/module-deps",
    "keywords": [
        "dependency",
        "graph",
        "browser",
        "require",
        "module",
        "exports",
        "json"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ahdinosaur"
        },
        {
            "name": "jmm"
        },
        {
            "name": "leichtgewicht"
        },
        {
            "name": "mellowmelon"
        },
        {
            "name": "substack"
        },
        {
            "name": "terinjokes"
        },
        {
            "name": "yoshuawuyts"
        },
        {
            "name": "zertosh"
        }
    ],
    "name": "module-deps",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/module-deps.git"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "version": "4.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
