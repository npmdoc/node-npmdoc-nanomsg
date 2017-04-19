# npmdoc-nanomsg

#### api documentation for  [nanomsg (v3.3.0)](https://github.com/nickdesaulniers/node-nanomsg#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nanomsg.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nanomsg) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nanomsg.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nanomsg)

#### Node bindings for nanomsg

[![NPM](https://nodei.co/npm/nanomsg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nanomsg)

- [https://npmdoc.github.io/node-npmdoc-nanomsg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nanomsg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nanomsg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nanomsg/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nanomsg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nanomsg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Desaulniers",
        "url": "http://nickdesaulniers.github.io"
    },
    "bugs": {
        "url": "https://github.com/nickdesaulniers/node-nanomsg/issues"
    },
    "contributors": [
        {
            "name": "a0000778",
            "url": "https://github.com/a0000778"
        },
        {
            "name": "Adam Biro",
            "url": "https://github.com/sirudog"
        },
        {
            "name": "Ant Skelton",
            "url": "https://github.com/blowback"
        },
        {
            "name": "Benjamin Byholm",
            "url": "https://github.com/kkoopa"
        },
        {
            "name": "Bent Cardan",
            "url": "https://github.com/reqshark"
        },
        {
            "name": "Deepak Prabhakara",
            "url": "https://github.com/deepakprabhakara"
        },
        {
            "name": "Flynn Joffray",
            "url": "https://github.com/nucleardreamer"
        },
        {
            "name": "m-ohuchi",
            "url": "https://github.com/m-ohuchi"
        },
        {
            "name": "Michele Comignano",
            "url": "https://github.com/comick"
        },
        {
            "name": "Nick Desaulniers",
            "url": "https://github.com/nickdesaulniers"
        },
        {
            "name": "Tim Cameron Ryan",
            "url": "https://github.com/tcr"
        },
        {
            "name": "Trygve Lie",
            "url": "https://github.com/trygve-lie"
        }
    ],
    "dependencies": {
        "bindings": "1.2.1",
        "nan": "2.4"
    },
    "description": "Node bindings for nanomsg",
    "devDependencies": {
        "buffer-equals-polyfill": "1.0.0",
        "esformatter": "0.0.16",
        "tap-difflet": "0.3.0",
        "tap-nyan": "0.0.2",
        "tape": "~2.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "92d960b2e583425decac81e8bdb8eb9c14cc21f6",
        "tarball": "https://registry.npmjs.org/nanomsg/-/nanomsg-3.3.0.tgz"
    },
    "gitHead": "3b7b2429882675b8d9241a0a00d0e285f2061382",
    "gypfile": true,
    "homepage": "https://github.com/nickdesaulniers/node-nanomsg#readme",
    "keywords": [
        "nanomsg",
        "native",
        "binding",
        "addon",
        "nn",
        "nanømsg"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "nickdesaulniers"
        },
        {
            "name": "reqshark"
        }
    ],
    "name": "nanomsg",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nickdesaulniers/node-nanomsg.git"
    },
    "scripts": {
        "beaut": "find . -path ./node_modules -prune -or -name '*.js' -exec sh -c 'cp -a {} {}.tmp; esformatter {} >{}.tmp && mv {}.tmp {}' \\;",
        "install": "node-gyp rebuild",
        "symbols": "cd test && ruby mksymbols.rb > symbols.js",
        "test": "find test/*.js test/standalone/*.js | xargs -n 1 node | node_modules/tap-nyan/bin/cmd.js"
    },
    "version": "3.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
