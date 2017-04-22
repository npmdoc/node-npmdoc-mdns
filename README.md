# npmdoc-mdns

#### api documentation for  [mdns (v2.3.3)](http://agnat.github.com/node_mdns)  [![npm package](https://img.shields.io/npm/v/npmdoc-mdns.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mdns) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mdns.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mdns)

#### multicast DNS service discovery

[![NPM](https://nodei.co/npm/mdns.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mdns)

- [https://npmdoc.github.io/node-npmdoc-mdns/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mdns/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mdns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mdns/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mdns/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mdns/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mdns",
    "version": "2.3.3",
    "description": "multicast DNS service discovery",
    "main": "./lib/mdns.js",
    "scripts": {
        "test": "node utils/testrun"
    },
    "keywords": [
        "zeroconf",
        "bonjour",
        "dns_sd",
        "mDNSResponder"
    ],
    "devDependencies": {
        "ejs": "*",
        "less": "*",
        "mkdirp": "*",
        "nopt": "*",
        "slide": "*",
        "glob": "*",
        "ncp": "*",
        "minimatch": "*",
        "proxyquire": "^1.7.3"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/agnat/node_mdns.git"
    },
    "homepage": "http://agnat.github.com/node_mdns",
    "bugs": {
        "url": "http://github.com/agnat/node_mdns/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/agnat/node_mdns/raw/master/LICENSE"
        }
    ],
    "author": {
        "name": "David Siegel",
        "github": "agnat"
    },
    "contributors": [
        {
            "name": "Orlando Vazquez",
            "url": "http://or.lan.do/",
            "github": "orlandov"
        },
        {
            "name": "Ryan Dahl",
            "url": "http://four.livejournal.com/",
            "github": "ry"
        },
        {
            "name": "Dominic Tarr",
            "url": "http://twitter.com/dominictarr",
            "github": "dominictarr"
        },
        {
            "name": "Emil Stenqvist",
            "github": "emilisto"
        },
        {
            "name": "Toby Ealden",
            "github": "TobyEalden"
        },
        {
            "name": "Cong Liu",
            "github": "ghostoy"
        },
        {
            "name": "Tian Zhang",
            "github": "KhaosT"
        }
    ],
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "~2.3.0"
    },
    "gypfile": true,
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
