# npmtest-grunt-accessibility

#### basic test coverage for  [grunt-accessibility (v5.0.0)](https://github.com/yargalot/grunt-accessibility)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-accessibility.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-accessibility) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-accessibility.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-accessibility)

#### Grade your site's accessibility and generate a report from different WCAG levels

[![NPM](https://nodei.co/npm/grunt-accessibility.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-accessibility)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-accessibility/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-accessibility/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-accessibility/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-accessibility/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-accessibility/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-accessibility/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-accessibility/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-accessibility/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-accessibility/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-accessibility/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-accessibility",
    "description": "Grade your site's accessibility and generate a report from different WCAG levels",
    "version": "5.0.0",
    "homepage": "https://github.com/yargalot/grunt-accessibility",
    "author": "Steven John Miller (http://www.stevenjohnmiller.com/)",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yargalot/grunt-accessibility.git"
    },
    "bugs": {
        "url": "https://github.com/yargalot/grunt-accessibility/issues"
    },
    "license": "MIT",
    "main": "tasks/grunt-accessibility.js",
    "engines": {
        "node": ">=4.0.0"
    },
    "scripts": {
        "prepublish": "grunt test",
        "test": "grunt test"
    },
    "dependencies": {
        "access-sniff": "^3.0.0"
    },
    "devDependencies": {
        "grunt": "^1.0.0",
        "grunt-bump": "^0.8.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "load-grunt-tasks": "^3.5.0",
        "time-grunt": "^1.3.0"
    },
    "peerDependencies": {
        "grunt": ">=0.4.5"
    },
    "keywords": [
        "gruntplugin",
        "accessibility",
        "a11y",
        "analysis",
        "report",
        "WCAG"
    ],
    "files": [
        "tasks"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
