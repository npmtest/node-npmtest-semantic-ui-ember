# npmtest-semantic-ui-ember

#### basic test coverage for  [semantic-ui-ember (v2.0.1)](http://www.semantic-ui.com)  [![npm package](https://img.shields.io/npm/v/npmtest-semantic-ui-ember.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-semantic-ui-ember) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-semantic-ui-ember.svg)](https://travis-ci.org/npmtest/node-npmtest-semantic-ui-ember)

#### The Official Semantic UI Addon for Ember applications

[![NPM](https://nodei.co/npm/semantic-ui-ember.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/semantic-ui-ember)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-semantic-ui-ember/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-semantic-ui-ember/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-semantic-ui-ember/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/test-report.html](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-semantic-ui-ember/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-semantic-ui-ember/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-semantic-ui-ember/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-semantic-ui-ember/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-semantic-ui-ember/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "semantic-ui-ember",
    "version": "2.0.1",
    "description": "The Official Semantic UI Addon for Ember applications",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "author": "",
    "title": "Semantic UI Ember",
    "homepage": "http://www.semantic-ui.com",
    "contributors": [
        {
            "name": "Nathan Palmer"
        },
        {
            "name": "Aaron Hansen"
        }
    ],
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/Semantic-Org/Semantic-UI-Ember.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.7",
        "ember-promise-tools": "1.0.0",
        "ember-runtime-enumerable-includes-polyfill": "^1.0.1",
        "ember-string-ishtmlsafe-polyfill": "1.0.1"
    },
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "ember-ajax": "^2.4.1",
        "ember-cli": "2.10.0",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-clipboard": "0.4.1",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-github-pages": "0.1.2",
        "ember-cli-htmlbars": "^1.0.10",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-jshint": "^2.0.1",
        "ember-cli-qunit": "^3.0.2",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-composable-helpers": "1.1.2",
        "ember-data": "^2.10.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.3",
        "ember-resolver": "^2.0.3",
        "loader.js": "^4.0.10",
        "tape": "^4.6.0"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "http://Semantic-Org.github.io/Semantic-UI-Ember"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
