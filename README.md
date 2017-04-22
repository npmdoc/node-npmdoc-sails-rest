# npmdoc-sails-rest

#### api documentation for  [sails-rest (v0.1.1)](https://github.com/zohararad/sails-rest#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-rest.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-rest) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-rest.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-rest)

#### rest adapter for Sails / Waterline

[![NPM](https://nodei.co/npm/sails-rest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-rest)

- [https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zohar Arad"
    },
    "bugs": {
        "url": "https://github.com/zohararad/sails-rest/issues"
    },
    "dependencies": {
        "async": "^1.4.2",
        "lodash": "^3.9.3",
        "restify": "^3.0.3",
        "superagent": "^1.2.0"
    },
    "description": "rest adapter for Sails / Waterline",
    "devDependencies": {
        "body-parser": "^1.12.4",
        "captains-log": "~0.11.0",
        "express": "^4.12.4",
        "mocha": "*",
        "multer": "^0.1.8",
        "sails-memory": "^0.10.4",
        "waterline-adapter-tests": "~0.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ad55c8fd1691d736e33b2409bfa7f0d8176c82b1",
        "tarball": "https://registry.npmjs.org/sails-rest/-/sails-rest-0.1.1.tgz"
    },
    "gitHead": "484898cec7af6c1d4eaff4cad100037d794edd37",
    "homepage": "https://github.com/zohararad/sails-rest#readme",
    "keywords": [
        "rest",
        "adapter",
        "sails",
        "waterline",
        "sails.js",
        "plugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "zohararad"
        }
    ],
    "name": "sails-rest",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zohararad/sails-rest.git"
    },
    "scripts": {
        "test": "node test/integration/runner -R spec -b"
    },
    "version": "0.1.1",
    "waterlineAdapter": {
        "type": "rest",
        "interfaces": [
            "semantic"
        ],
        "waterlineVersion": "~0.10.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
