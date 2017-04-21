# npmtest-ember-source

#### basic test coverage for  [ember-source (v2.12.1)](http://emberjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-source.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-source) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-source.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-source)

#### A JavaScript framework for creating ambitious web applications

[![NPM](https://nodei.co/npm/ember-source.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-source)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-source/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-source/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-source/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-source/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-source/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-source/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-source/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-source/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-source/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-source/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-source/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-source/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-source/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-source/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-source/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-source/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-source/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-source/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-source/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-source/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-source/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-source",
    "version": "2.12.1",
    "description": "A JavaScript framework for creating ambitious web applications",
    "keywords": [
        "ember-addon"
    ],
    "homepage": "http://emberjs.com/",
    "bugs": {
        "url": "https://github.com/emberjs/ember.js/issues"
    },
    "license": "MIT",
    "files": [
        "blueprints",
        "dist",
        "!dist/ember-tests.prod.js",
        "!dist/ember-tests.js",
        "!dist/qunit",
        "!dist/jquery",
        "!dist/tests",
        "vendor/ember",
        "index.js"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/emberjs/ember.js.git"
    },
    "scripts": {
        "build": "ember build --environment production",
        "docs": "ember ember-cli-yuidoc",
        "release": "node scripts/release.js",
        "sauce:launch": "ember sauce:launch",
        "start": "ember serve",
        "pretest": "ember build",
        "test": "node bin/run-tests.js",
        "test:blueprints": "node node-tests/nodetest-runner.js",
        "test:sauce": "node bin/run-sauce-tests.js",
        "test:testem": "testem -f testem.dist.json"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.6",
        "broccoli-merge-trees": "^1.1.4",
        "ember-cli-get-component-path-option": "^1.0.0",
        "ember-cli-normalize-entity-name": "^1.0.0",
        "ember-cli-path-utils": "^1.0.0",
        "ember-cli-string-utils": "^1.0.0",
        "ember-cli-test-info": "^1.0.0",
        "ember-cli-valid-component-name": "^1.0.0",
        "ember-cli-version-checker": "^1.1.7",
        "jquery": "^3.1.1",
        "resolve": "^1.1.7",
        "rsvp": "^3.4.0",
        "simple-dom": "^0.3.0"
    },
    "devDependencies": {
        "aws-sdk": "~2.2.43",
        "babel-plugin-feature-flags": "^0.2.3",
        "babel-plugin-filter-imports": "~0.2.0",
        "backburner.js": "^0.3.1",
        "broccoli-rollup": "^1.0.3",
        "broccoli-string-replace": "^0.1.1",
        "broccoli-uglify-sourcemap": "^1.4.2",
        "chalk": "^1.1.1",
        "dag-map": "^2.0.1",
        "ember-cli": "2.10.0",
        "ember-cli-blueprint-test-helpers": "^0.12.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-sauce": "^2.0.0",
        "ember-cli-yuidoc": "0.8.4",
        "ember-publisher": "0.0.7",
        "emberjs-build": "0.19.0",
        "express": "^4.5.0",
        "finalhandler": "^0.4.0",
        "git-repo-info": "^1.1.4",
        "git-repo-version": "^0.3.1",
        "github": "^0.2.3",
        "glimmer-engine": "^0.19.4",
        "glob": "^5.0.13",
        "html-differ": "^1.3.4",
        "mocha": "^2.4.5",
        "qunit-extras": "^1.5.0",
        "qunit-phantomjs-runner": "^2.2.0",
        "qunitjs": "^1.22.0",
        "route-recognizer": "^0.3.0",
        "router_js": "^1.2.4",
        "serve-static": "^1.10.0",
        "simple-dom": "^0.3.0",
        "testem": "^1.14.2"
    },
    "ember-addon": {
        "after": "ember-cli-legacy-blueprints"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
