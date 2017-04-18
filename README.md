# npmdoc-static-site-generator-webpack-plugin

#### api documentation for  [static-site-generator-webpack-plugin (v3.4.1)](https://github.com/markdalgleish/static-site-generator-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmdoc-static-site-generator-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-static-site-generator-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-static-site-generator-webpack-plugin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-static-site-generator-webpack-plugin)

#### Minimal, unopinionated static site generator powered by webpack

[![NPM](https://nodei.co/npm/static-site-generator-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/static-site-generator-webpack-plugin)

- [https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-static-site-generator-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mark Dalgleish"
    },
    "bugs": {
        "url": "https://github.com/markdalgleish/static-site-generator-webpack-plugin/issues"
    },
    "dependencies": {
        "bluebird": "^3.0.5",
        "cheerio": "^0.22.0",
        "eval": "^0.1.0",
        "url": "^0.11.0",
        "webpack-sources": "^0.2.0"
    },
    "description": "Minimal, unopinionated static site generator powered by webpack",
    "devDependencies": {
        "async": "^2.0.1",
        "babel-core": "^6.2.1",
        "babel-loader": "^6.2.0",
        "babel-preset-es2015": "^6.1.18",
        "chai": "^3.4.1",
        "compression-webpack-plugin": "^0.3.1",
        "coveralls": "^2.11.4",
        "ejs": "^2.3.4",
        "glob": "^7.0.3",
        "istanbul": "^0.4.1",
        "mocha": "^3.0.2",
        "rimraf": "^2.4.4",
        "webpack": "^1.12.10",
        "webpack-stats-plugin": "^0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6ee22468830bc546798a37e0fca6fd699cc93b81",
        "tarball": "https://registry.npmjs.org/static-site-generator-webpack-plugin/-/static-site-generator-webpack-plugin-3.4.1.tgz"
    },
    "gitHead": "09001fe4ba442c43a747e5162fbac37e5cb0ddf2",
    "homepage": "https://github.com/markdalgleish/static-site-generator-webpack-plugin",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "markdalgleish"
        }
    ],
    "name": "static-site-generator-webpack-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/markdalgleish/static-site-generator-webpack-plugin.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul cover _mocha test -- --timeout 20000"
    },
    "version": "3.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
