# npmtest-react-native-swiper

#### basic test coverage for  [react-native-swiper (v1.5.4)](https://github.com/leecade/react-native-swiper#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-swiper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-swiper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-swiper.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-swiper)

#### Swiper component for React Native.

[![NPM](https://nodei.co/npm/react-native-swiper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-swiper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-swiper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-swiper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-swiper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-swiper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-swiper/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-native-swiper/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-native-swiper/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-swiper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-swiper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-swiper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-swiper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-swiper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-swiper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-swiper/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-swiper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-swiper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-swiper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-swiper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-swiper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-swiper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-swiper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-swiper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-swiper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-swiper",
    "keywords": [
        "react-component",
        "react-native",
        "ios"
    ],
    "version": "1.5.4",
    "description": "Swiper component for React Native.",
    "main": "index.js",
    "scripts": {
        "start": "react-native start",
        "lint": "standard | snazzy",
        "update": "updtr",
        "precommit": "git diff --name-only --cached --relative | grep '\\.jsx\\?$' | xargs standard | snazzy; if [ $? -ne 0 ]; then exit 1; fi",
        "test": "npm run lint"
    },
    "pre-commit": {
        "run": [
            "precommit"
        ],
        "silent": true
    },
    "standard": {
        "parser": "babel-eslint",
        "global": [
            "__DEV__",
            "FormData",
            "requestAnimationFrame",
            "alert",
            "setImmediate",
            "fetch"
        ],
        "ignore": [
            "dist/",
            "mock/",
            "node_modules/"
        ]
    },
    "ava": {
        "babel": "inherit",
        "require": []
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/leecade/react-native-swiper.git"
    },
    "author": "",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/leecade/react-native-swiper/issues"
    },
    "homepage": "https://github.com/leecade/react-native-swiper#readme",
    "devDependencies": {
        "babel-eslint": "^7.1.1",
        "rimraf": "^2.5.4",
        "snazzy": "^5.0.0",
        "standard": "^8.5.0",
        "updtr": "^0.2.3"
    },
    "dependencies": {},
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
