# api documentation for  [karma-phantomjs-launcher (v1.0.4)](https://github.com/karma-runner/karma-phantomjs-launcher#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-phantomjs-launcher.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-phantomjs-launcher) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-phantomjs-launcher.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-phantomjs-launcher)
#### A Karma plugin. Launcher for PhantomJS.

[![NPM](https://nodei.co/npm/karma-phantomjs-launcher.png?downloads=true)](https://www.npmjs.com/package/karma-phantomjs-launcher)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-phantomjs-launcher/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-karma-phantomjs-launcher_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-phantomjs-launcher/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-phantomjs-launcher/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-phantomjs-launcher/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jina",
        "email": "vojta.jina@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-phantomjs-launcher/issues"
    },
    "contributors": [
        {
            "name": "Vojta Jina",
            "email": "vojta.jina@gmail.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Shinnosuke Watanabe",
            "email": "snnskwtnb@gmail.com"
        },
        {
            "name": "Jurko Gospodnetić",
            "email": "jurko.gospodnetic@pke.hr"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "Sylvain Hamel",
            "email": "sylvainhamel0@gmail.com"
        },
        {
            "name": "Huafu Gandon",
            "email": "huafu.gandon@gmail.com"
        },
        {
            "name": "Dan Siwiec",
            "email": "daniel.siwiec@gmail.com"
        },
        {
            "name": "Rob Barreca",
            "email": "rob.barreca@inmobi.com"
        },
        {
            "name": "Sergey Bondarenko",
            "email": "enterit@gmail.com"
        },
        {
            "name": "nherzing",
            "email": "nherzing@gmail.com"
        },
        {
            "name": "Chad Smith",
            "email": "chad@configit.com"
        },
        {
            "name": "sylvain-hamel",
            "email": "sylvainhamel0@gmail.com"
        },
        {
            "name": "Edward Hutchins",
            "email": "eahutchins@gmail.com"
        },
        {
            "name": "Eryk Napierała",
            "email": "eryk.piast@gmail.com"
        },
        {
            "name": "Jason Dobry",
            "email": "jason.dobry@gmail.com"
        },
        {
            "name": "Joel Mukuthu",
            "email": "jmu@one.com"
        },
        {
            "name": "Jonathan Park",
            "email": "jpark@daptiv.com"
        },
        {
            "name": "Leigh Tarasenko",
            "email": "leightarasenko@gmail.com"
        },
        {
            "name": "Mark Derbecker",
            "email": "mark.derbecker@seeq.com"
        },
        {
            "name": "Mark Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Nick Malaguti",
            "email": "nmalaguti@palantir.com"
        }
    ],
    "dependencies": {
        "lodash": "^4.0.1",
        "phantomjs-prebuilt": "^2.1.7"
    },
    "description": "A Karma plugin. Launcher for PhantomJS.",
    "devDependencies": {
        "eslint": "^1.0.0",
        "eslint-config-standard": "^4.0.0",
        "eslint-plugin-react": "^3.2.0",
        "eslint-plugin-standard": "^1.3.1",
        "grunt": "~0.4.1",
        "grunt-auto-release": "~0.0.2",
        "grunt-bump": "~0.3.1",
        "grunt-conventional-changelog": "^1.2.2",
        "grunt-eslint": "^17.0.0",
        "grunt-karma": "1.x || ^0.12.1",
        "grunt-npm": "~0.0.2",
        "jasmine-core": "^2.3.4",
        "karma": "1.x || ^0.13.6",
        "karma-jasmine": "1.x || ^0.3.5",
        "load-grunt-tasks": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d23ca34801bda9863ad318e3bb4bd4062b13acd2",
        "tarball": "https://registry.npmjs.org/karma-phantomjs-launcher/-/karma-phantomjs-launcher-1.0.4.tgz"
    },
    "gitHead": "eb0ca03d1938ed7b18da572284d3d52e2c1b70c9",
    "homepage": "https://github.com/karma-runner/karma-phantomjs-launcher#readme",
    "keywords": [
        "karma-plugin",
        "karma-launcher",
        "phantomjs"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        }
    ],
    "name": "karma-phantomjs-launcher",
    "optionalDependencies": {},
    "peerDependencies": {
        "karma": ">=0.9"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-phantomjs-launcher.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "1.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module karma-phantomjs-launcher](#apidoc.module.karma-phantomjs-launcher)



# <a name="apidoc.module.karma-phantomjs-launcher"></a>[module karma-phantomjs-launcher](#apidoc.module.karma-phantomjs-launcher)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
