# apidoc-lite
this zero-dependency package will auto-generate documentation for your npm-package with zero-config

# live web demo
- [https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.example.html](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.example.html)

[![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.testExampleSh.browser.%252Ftmp%252Fapidoc.html.png)](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.example.html)



[![travis-ci.org build-status](https://api.travis-ci.org/kaizhu256/node-apidoc-lite.svg)](https://travis-ci.org/kaizhu256/node-apidoc-lite) [![coverage](https://kaizhu256.github.io/node-apidoc-lite/build/coverage.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build/coverage.html/index.html)

[![NPM](https://nodei.co/npm/apidoc-lite.png?downloads=true)](https://www.npmjs.com/package/apidoc-lite)

[![build commit status](https://kaizhu256.github.io/node-apidoc-lite/build/build.badge.svg)](https://travis-ci.org/kaizhu256/node-apidoc-lite)

| git-branch : | [master](https://github.com/kaizhu256/node-apidoc-lite/tree/master) | [beta](https://github.com/kaizhu256/node-apidoc-lite/tree/beta) | [alpha](https://github.com/kaizhu256/node-apidoc-lite/tree/alpha)|
|--:|:--|:--|:--|
| test-report : | [![test-report](https://kaizhu256.github.io/node-apidoc-lite/build..master..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build..master..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-apidoc-lite/build..alpha..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build..alpha..travis-ci.org/test-report.html)|
| coverage : | [![coverage](https://kaizhu256.github.io/node-apidoc-lite/build..master..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build..master..travis-ci.org/coverage.html/index.html) | [![coverage](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/coverage.html/index.html) | [![coverage](https://kaizhu256.github.io/node-apidoc-lite/build..alpha..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-apidoc-lite/build..alpha..travis-ci.org/coverage.html/index.html)|
| build-artifacts : | [![build-artifacts](https://kaizhu256.github.io/node-apidoc-lite/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-apidoc-lite/tree/gh-pages/build..master..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-apidoc-lite/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-apidoc-lite/tree/gh-pages/build..beta..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-apidoc-lite/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-apidoc-lite/tree/gh-pages/build..alpha..travis-ci.org)|

[![npmPackageListing](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.npmPackageListing.svg)](https://github.com/kaizhu256/node-apidoc-lite)

![npmPackageDependencyTree](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.npmPackageDependencyTree.svg)



# table of contents
1. [cdn download](#cdn-download)
1. [documentation](#documentation)
1. [quickstart shell example](#quickstart-shell-example)
1. [extra screenshots](#extra-screenshots)
1. [package.json](#packagejson)
1. [changelog of last 50 commits](#changelog-of-last-50-commits)
1. [internal build script](#internal-build-script)
1. [misc](#misc)



# cdn download
- [https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/app/assets.apidoc.js](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/app/assets.apidoc.js)



# documentation
#### cli help
![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.npmPackageCliHelp.svg)

#### api doc
- [https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.html](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.html)

[![apidoc](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.html)

#### todo
- none

#### changelog 2019.8.16
- npm publish 2019.8.16
- update build
- none

#### this package requires
- darwin or linux os



# quickstart shell example
#### to run this example, follow the instruction in the script below
- [example.sh](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/example.sh)
```shell
# example.sh

# this shell script will auto-generate documentation for the mysql npm-package with zero-config

# 1. npm install apidoc-lite
npm install apidoc-lite --prefix .
# 2. npm install mysql
npm install mysql
# 3. auto-generate documentation for the mysql npm-package with zero-config
./node_modules/.bin/apidoc-lite mysql > /tmp/apidoc.html
# 4. open /tmp/apidoc.html to view the auto-generated mysql documentation
```

#### output from browser
[![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.testExampleSh.browser.%252Ftmp%252Fapidoc.html.png)](https://kaizhu256.github.io/node-apidoc-lite/build..beta..travis-ci.org/apidoc.example.html)

#### output from shell
![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.testExampleSh.svg)



# extra screenshots
1. [https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)
[![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)

1. [https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)
[![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)

1. [https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)
[![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)



# package.json
```json
{
    "author": "kai zhu <kaizhu256@gmail.com>",
    "bin": {
        "apidoc-lite": "lib.apidoc.js"
    },
    "description": "this zero-dependency package will auto-generate documentation for your npm-package with zero-config",
    "devDependencies": {
        "electron-lite": "kaizhu256/node-electron-lite#alpha",
        "utility2": "kaizhu256/node-utility2#alpha"
    },
    "engines": {
        "node": ">=8.0"
    },
    "homepage": "https://github.com/kaizhu256/node-apidoc-lite",
    "keywords": [
        "apidoc",
        "documentation-generator",
        "doxygen"
    ],
    "license": "MIT",
    "main": "lib.apidoc.js",
    "name": "apidoc-lite",
    "nameAliasPublish": "npmdoc",
    "nameLib": "apidoc",
    "nameOriginal": "apidoc-lite",
    "os": [
        "darwin",
        "linux"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/kaizhu256/node-apidoc-lite.git"
    },
    "scripts": {
        "build-ci": "./npm_scripts.sh",
        "env": "env",
        "eval": "./npm_scripts.sh",
        "heroku-postbuild": "./npm_scripts.sh",
        "postinstall": "./npm_scripts.sh",
        "start": "./npm_scripts.sh",
        "test": "./npm_scripts.sh",
        "utility2": "./npm_scripts.sh"
    },
    "version": "2019.8.16"
}
```



# changelog of last 50 commits
[![screenshot](https://kaizhu256.github.io/node-apidoc-lite/build/screenshot.gitLog.svg)](https://github.com/kaizhu256/node-apidoc-lite/commits)



# internal build script
- build_ci.sh
```shell
# build_ci.sh

# this shell script will run the build for this package

shBuildCiAfter () {(set -e
    shDeployCustom
    # shDeployGithub
    # shDeployHeroku
    # bug-workaround for "npm install [package name] removes packages"
    # https://github.com/npm/npm/issues/17379
    # https://github.com/travis-ci/travis-ci/issues/4653#issuecomment-379397837
    if [ "$TRAVIS" ] && (dpkg --compare-versions "$(npm -v)" lt 5.8)
    then
         npm i -g npm@5.8
    fi
    shReadmeTest example.sh
    # screenshot
    MODE_BUILD=testExampleSh shBrowserScreenshot file:///tmp/apidoc.html
    cp /tmp/apidoc.html "$npm_config_dir_build/apidoc.example.html"
)}

shBuildCiBefore () {(set -e
    shNpmTestPublished
    shReadmeTest example.js
)}

# run shBuildCi
eval "$(utility2 source)"
shBuildCi
```



# misc
- this package was created with [utility2](https://github.com/kaizhu256/node-utility2)
