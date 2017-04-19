# npmtest-jsx-control-statements

#### test coverage for  [jsx-control-statements (v3.1.5)](https://github.com/AlexGilleran/jsx-control-statements#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jsx-control-statements.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsx-control-statements) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsx-control-statements.svg)](https://travis-ci.org/npmtest/node-npmtest-jsx-control-statements)

#### Neater control statements (if/for) for jsx

[![NPM](https://nodei.co/npm/jsx-control-statements.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsx-control-statements)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsx-control-statements/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsx-control-statements/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsx-control-statements/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsx-control-statements/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsx-control-statements/build/test-report.html](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsx-control-statements/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsx-control-statements/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsx-control-statements/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsx-control-statements/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsx-control-statements/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex Gilleran"
    },
    "bugs": {
        "url": "https://github.com/AlexGilleran/jsx-control-statements/issues"
    },
    "dependencies": {
        "babel-core": "^6.1.2",
        "babel-plugin-syntax-jsx": "^6.1.18"
    },
    "description": "Neater control statements (if/for) for jsx",
    "devDependencies": {
        "babel-eslint": "^6.0.3",
        "babel-preset-react": "^6.1.2",
        "chai": "^3.5.0",
        "chai-spies": "^0.7.1",
        "coveralls": "^2.11.6",
        "eslint": "^3.4.0",
        "eslint-config-airbnb": "^10.0.1",
        "eslint-plugin-jsx-control-statements": "^2.1.0",
        "eslint-plugin-react": "^6.2.0",
        "istanbul": "^0.4.1",
        "mocha": "^3.0.2",
        "react": "^15.3.1",
        "react-dom": "^15.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a9237aad3e5af6a133a1c3c1fcbbd360bbb5df7c",
        "tarball": "https://registry.npmjs.org/jsx-control-statements/-/jsx-control-statements-3.1.5.tgz"
    },
    "gitHead": "a8a4834ac07425fbc2baaf693c4e94af556ff1f0",
    "homepage": "https://github.com/AlexGilleran/jsx-control-statements#readme",
    "keywords": [
        "react",
        "jsx",
        "if",
        "else",
        "for",
        "each",
        "loop",
        "babel",
        "react-component"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "alexgilleran"
        }
    ],
    "name": "jsx-control-statements",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/AlexGilleran/jsx-control-statements.git"
    },
    "scripts": {
        "cover": "istanbul cover -x \"**/spec/**\" node_modules/mocha/bin/_mocha spec/*.js",
        "lint": "eslint src spec",
        "test": "mocha spec/*.js"
    },
    "version": "3.1.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
