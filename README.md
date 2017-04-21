# npmdoc-query-overpass

#### api documentation for  query-overpass (v1.4.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-query-overpass.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-query-overpass) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-query-overpass.svg)](https://travis-ci.org/npmdoc/node-npmdoc-query-overpass)

#### Make queries to OpenStreetMap's overpass API and output as GeoJSON

[![NPM](https://nodei.co/npm/query-overpass.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/query-overpass)

- [https://npmdoc.github.io/node-npmdoc-query-overpass/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-query-overpass/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-query-overpass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-query-overpass/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-query-overpass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-query-overpass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "query-overpass",
    "version": "1.4.0",
    "description": "Make queries to OpenStreetMap's overpass API and output as GeoJSON",
    "repository": "git@github.com:perliedman/query-overpass.git",
    "main": "index.js",
    "scripts": {
        "test": "tape test/*.js | faucet"
    },
    "browser": {
        "request": "xhr"
    },
    "bin": {
        "query-overpass": "cli.js"
    },
    "keywords": [
        "osm",
        "overpass",
        "geojson"
    ],
    "author": "Per Liedman <per@liedman.net>",
    "license": "ISC",
    "dependencies": {
        "JSONStream": "^1.3.1",
        "concat-stream": "^1.6.0",
        "minimist": "^1.2.0",
        "osmtogeojson": "^2.2.12",
        "request": "^2.81.0",
        "xhr": "^2.4.0"
    },
    "devDependencies": {
        "faucet": "0.0.1",
        "tape": "^4.6.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
