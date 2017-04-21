# npmdoc-packagecheck

#### api documentation for  packagecheck (v0.2.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-packagecheck.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-packagecheck) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-packagecheck.svg)](https://travis-ci.org/npmdoc/node-npmdoc-packagecheck)

#### Checks to see if package dependencies used by a Meteor package are themselves up to date.

[![NPM](https://nodei.co/npm/packagecheck.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/packagecheck)

- [https://npmdoc.github.io/node-npmdoc-packagecheck/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-packagecheck/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-packagecheck/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-packagecheck/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-packagecheck/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-packagecheck/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "packagecheck",
    "version": "0.2.1",
    "description": "Checks to see if package dependencies used by a Meteor package are themselves up to date.",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "author": "Timothy Armes <tim@timothyarmes.com> (http://www.timothyarmes.com)",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/timothyarmes/packagecheck.git"
    },
    "preferGlobal": true,
    "bin": {
        "packagecheck": "run"
    },
    "dependencies": {
        "minimist": "^1.1.2",
        "selfupdate": "^1.1.0",
        "sync": "^0.2.5",
        "sync-exec": "^0.6.1",
        "underscore": "^1.8.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
