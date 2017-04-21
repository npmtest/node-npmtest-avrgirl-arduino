# npmtest-avrgirl-arduino

#### basic test coverage for  [avrgirl-arduino (v2.0.0)](https://github.com/noopkat/avrgirl-arduino)  [![npm package](https://img.shields.io/npm/v/npmtest-avrgirl-arduino.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-avrgirl-arduino) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-avrgirl-arduino.svg)](https://travis-ci.org/npmtest/node-npmtest-avrgirl-arduino)

#### A NodeJS library for flashing compiled sketch files to Arduino microcontroller boards.

[![NPM](https://nodei.co/npm/avrgirl-arduino.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/avrgirl-arduino)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-avrgirl-arduino/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-avrgirl-arduino/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-avrgirl-arduino/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/test-report.html](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-avrgirl-arduino/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "avrgirl-arduino",
    "version": "2.0.0",
    "description": "A NodeJS library for flashing compiled sketch files to Arduino microcontroller boards.",
    "bin": "./bin/cli.js",
    "main": "avrgirl-arduino.js",
    "scripts": {
        "test": "gulp test",
        "cover": "istanbul cover ./tests/*.spec.js && istanbul-coveralls"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/noopkat/avrgirl-arduino.git"
    },
    "keywords": [
        "arduino",
        "avr",
        "avr109",
        "stk500",
        "avrdude",
        "avrgirl",
        "avrg"
    ],
    "author": "Suz Hinton",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/noopkat/avrgirl-arduino/issues"
    },
    "homepage": "https://github.com/noopkat/avrgirl-arduino",
    "dependencies": {
        "async": "^2.1.2",
        "awty": "^0.1.0",
        "browser-serialport": "https://github.com/noopkat/browser-serialport#api-updates",
        "chip.avr.avr109": "^1.1.0",
        "colors": "^1.1.2",
        "graceful-fs": "^4.1.2",
        "intel-hex": "^0.1.1",
        "minimist": "^1.2.0",
        "serialport": "^4.0.1",
        "stk500": "https://github.com/noopkat/js-stk500v1#avrgirl",
        "stk500-v2": "^1.0.2"
    },
    "devDependencies": {
        "avrga-tester": "1.x",
        "gulp": "^3.9.0",
        "gulp-jscs": "^3.0.2",
        "gulp-jshint": "^2.0.3",
        "gulp-tape": "0.0.9",
        "istanbul": "^0.4.0",
        "istanbul-coveralls": "^1.0.3",
        "jshint": "^2.9.2",
        "jshint-stylish": "^2.1.0",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.2",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.1",
        "virtual-serialport": "^0.3.1"
    },
    "browser": {
        "graceful-fs": false,
        "serialport": "browser-serialport"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
