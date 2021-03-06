# npmdoc-node-ssh

#### api documentation for  [node-ssh (v4.2.2)](https://github.com/steelbrain/node-ssh#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-ssh.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-ssh) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-ssh.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-ssh)

#### SS2 with Promises

[![NPM](https://nodei.co/npm/node-ssh.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-ssh)

- [https://npmdoc.github.io/node-npmdoc-node-ssh/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-ssh/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-ssh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-ssh/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-ssh/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-ssh/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "steelbrain"
    },
    "bugs": {
        "url": "https://github.com/steelbrain/node-ssh/issues"
    },
    "dependencies": {
        "sb-promisify": "^2.0.1",
        "sb-scandir": "^1.0.0",
        "shell-escape": "^0.2.0",
        "ssh2": "^0.5.0"
    },
    "description": "SS2 with Promises",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-preset-steelbrain": "^5.0.0",
        "eslint-config-steelbrain": "^3.0.1",
        "flow-bin": "^0.44.0",
        "jasmine-fix": "^1.0.1",
        "pty.js": "^0.3.1",
        "ssh2-streams": "^0.1.6"
    },
    "directories": {},
    "dist": {
        "shasum": "8b3fecce1be20109d850029919de8eac25e900cb",
        "tarball": "https://registry.npmjs.org/node-ssh/-/node-ssh-4.2.2.tgz"
    },
    "gitHead": "44f6183f99b6851db424da2a4cc8230399f66111",
    "homepage": "https://github.com/steelbrain/node-ssh#readme",
    "keywords": [
        "ssh",
        "ssh2",
        "sftp"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "steelbrain"
        }
    ],
    "name": "node-ssh",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/steelbrain/node-ssh.git"
    },
    "scripts": {
        "build": "npm run clean; babel src --out-dir lib",
        "clean": "rm -rf lib",
        "test": "(apm test) && (flow check) && (eslint . )",
        "watch": "npm run clean; babel src --out-dir lib --watch"
    },
    "version": "4.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
