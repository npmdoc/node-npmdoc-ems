# npmdoc-ems

#### basic api documentation for  [ems (v1.4.4)](https://synsem.com/EMS.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-ems.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ems) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ems.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ems)

#### Persistent Shared Memory and Parallel Programming Model

[![NPM](https://nodei.co/npm/ems.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ems)

- [https://npmdoc.github.io/node-npmdoc-ems/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ems/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ems/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ems/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ems/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ems/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Synthetic Semantics"
    },
    "bugs": {
        "url": "https://github.com/syntheticsemantics/ems/issues"
    },
    "contributors": [
        {
            "name": "Jace A Mogill"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "ffi": "^2.0.0",
        "nan": "^2.1.0",
        "node-gyp": "^3.2.1"
    },
    "description": "Persistent Shared Memory and Parallel Programming Model",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "c0d3e5a6b7bd1ad44829111e7e1073ff561278c4",
        "tarball": "https://registry.npmjs.org/ems/-/ems-1.4.4.tgz"
    },
    "engines": {
        "node": ">=0.10.25"
    },
    "gitHead": "b2efeb20232eca400d24ce10eeec091e9421c2b7",
    "gypfile": true,
    "homepage": "https://synsem.com/EMS.js",
    "keywords": [
        "non volatile memory",
        "NVM",
        "NVMe",
        "multithreading",
        "multithreaded",
        "parallel",
        "parallelism",
        "concurrency",
        "shared memory",
        "multicore",
        "manycore",
        "transactional memory",
        "TM",
        "persistent memory",
        "pmem",
        "Extended Memory Semantics",
        "EMS"
    ],
    "license": "BSD-3-Clause",
    "main": "nodejs/ems.js",
    "maintainers": [
        {
            "name": "mogill"
        }
    ],
    "name": "ems",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/syntheticsemantics/ems.git"
    },
    "scripts": {
        "example": "cd Examples; node concurrent_Q_and_TM.js 8",
        "install": "node-gyp rebuild",
        "test": "cd Tests && rm -f EMSthreadStub.js && for test in 'ls *js'; do node $test 8; err=$?; echo $test \": ERROR=\" $err;  if [ $err -ne 0 ] ; then exit 1; fi; done"
    },
    "version": "1.4.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
