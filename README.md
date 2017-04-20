# npmtest-homebridge-plugin-chromecast

#### basic test coverage for  homebridge-plugin-chromecast (v0.0.6)  [![npm package](https://img.shields.io/npm/v/npmtest-homebridge-plugin-chromecast.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-homebridge-plugin-chromecast) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-homebridge-plugin-chromecast.svg)](https://travis-ci.org/npmtest/node-npmtest-homebridge-plugin-chromecast)

####

[![NPM](https://nodei.co/npm/homebridge-plugin-chromecast.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebridge-plugin-chromecast)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-homebridge-plugin-chromecast/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-homebridge-plugin-chromecast/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/test-report.html](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-homebridge-plugin-chromecast/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebridge-plugin-chromecast/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebridge-plugin-chromecast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebridge-plugin-chromecast/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-homebridge-plugin-chromecast/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebridge-plugin-chromecast",
    "version": "0.0.6",
    "description": "",
    "keywords": [
        "homebridge-plugin"
    ],
    "main": "index.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "dev": "DEBUG=* node_modules/.bin/homebridge -D -P ./ -U ./config"
    },
    "engines": {
        "node": ">=6.1.0",
        "homebridge": ">=0.3.4"
    },
    "repository": {
        "type": "git",
        "url": "https://bitbucket.org/robertherber/homebridge-chromecast"
    },
    "author": "",
    "license": "ISC",
    "dependencies": {
        "bluebird": "^3.4.1",
        "castv2-client": "^1.1.2",
        "hap-nodejs": "^0.3.2",
        "lodash": "^4.14.2",
        "mdns": "^2.3.3"
    },
    "devDependencies": {
        "homebridge": "^0.3.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
