# npmdoc-sails-rest

#### api documentation for  sails-rest (v0.1.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-rest.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-rest) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-rest.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-rest)

#### rest adapter for Sails / Waterline

[![NPM](https://nodei.co/npm/sails-rest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-rest)

- [https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sails-rest",
    "version": "0.1.1",
    "description": "rest adapter for Sails / Waterline",
    "main": "index.js",
    "scripts": {
        "test": "node test/integration/runner -R spec -b"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/zohararad/sails-rest.git"
    },
    "keywords": [
        "rest",
        "adapter",
        "sails",
        "waterline",
        "sails.js",
        "plugin"
    ],
    "author": "Zohar Arad",
    "license": "MIT",
    "readmeFilename": "README.md",
    "dependencies": {
        "async": "^1.4.2",
        "lodash": "^3.9.3",
        "restify": "^3.0.3",
        "superagent": "^1.2.0"
    },
    "devDependencies": {
        "body-parser": "^1.12.4",
        "captains-log": "~0.11.0",
        "express": "^4.12.4",
        "mocha": "*",
        "multer": "^0.1.8",
        "sails-memory": "^0.10.4",
        "waterline-adapter-tests": "~0.10.0"
    },
    "waterlineAdapter": {
        "type": "rest",
        "interfaces": [
            "semantic"
        ],
        "waterlineVersion": "~0.10.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
