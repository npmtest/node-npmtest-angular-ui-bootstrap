# npmtest-angular-ui-bootstrap

#### test coverage for  [angular-ui-bootstrap (v2.5.0)](http://angular-ui.github.io/bootstrap/)  [![npm package](https://img.shields.io/npm/v/npmtest-angular-ui-bootstrap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular-ui-bootstrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular-ui-bootstrap.svg)](https://travis-ci.org/npmtest/node-npmtest-angular-ui-bootstrap)

#### Native AngularJS (Angular) directives for Bootstrap

[![NPM](https://nodei.co/npm/angular-ui-bootstrap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular-ui-bootstrap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular-ui-bootstrap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular-ui-bootstrap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/test-report.html](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular-ui-bootstrap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular-ui-bootstrap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-ui-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-ui-bootstrap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular-ui-bootstrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "https://github.com/angular-ui/bootstrap/graphs/contributors"
    },
    "bugs": {
        "url": "https://github.com/angular-ui/bootstrap/issues"
    },
    "dependencies": {},
    "description": "Native AngularJS (Angular) directives for Bootstrap",
    "devDependencies": {
        "angular": "1.6.1",
        "angular-mocks": "1.6.1",
        "angular-sanitize": "1.6.1",
        "grunt": "^0.4.5",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-concat": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-ddescribe-iit": "0.0.6",
        "grunt-eslint": "^17.3.1",
        "grunt-html2js": "^0.3.0",
        "grunt-karma": "^0.12.0",
        "jasmine-core": "^2.2.0",
        "karma": "0.13.22",
        "karma-chrome-launcher": "^0.2.0",
        "karma-coverage": "^0.5.0",
        "karma-firefox-launcher": "^0.1.4",
        "karma-jasmine": "^0.3.5",
        "load-grunt-tasks": "^3.3.0",
        "lodash": "^4.1.0",
        "marked": "^0.3.5",
        "node-static": "^0.7.8",
        "semver": "^5.0.1",
        "shelljs": "^0.6.0"
    },
    "directories": {
        "lib": "src/"
    },
    "dist": {
        "shasum": "2facefb915386655dc5f44150258032517236d01",
        "tarball": "https://registry.npmjs.org/angular-ui-bootstrap/-/angular-ui-bootstrap-2.5.0.tgz"
    },
    "files": [
        "index.js",
        "dist/",
        "src/",
        "template/"
    ],
    "gitHead": "b90485b2a42753084523a9a63ab96477b8b47c0d",
    "homepage": "http://angular-ui.github.io/bootstrap/",
    "keywords": [
        "angularjs",
        "angular",
        "bootstrap",
        "ui"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "foxandxss"
        },
        {
            "name": "wesleycho"
        }
    ],
    "name": "angular-ui-bootstrap",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/angular-ui/bootstrap.git"
    },
    "scripts": {
        "demo": "grunt after-test && static dist -a 0.0.0.0 -H '{\"Cache-Control\": \"no-cache, must-revalidate\"}'",
        "test": "grunt"
    },
    "version": "2.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
