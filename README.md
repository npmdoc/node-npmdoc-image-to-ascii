# npmdoc-image-to-ascii

#### api documentation for  [image-to-ascii (v3.0.7)](https://github.com/IonicaBizau/image-to-ascii)  [![npm package](https://img.shields.io/npm/v/npmdoc-image-to-ascii.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-image-to-ascii) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-image-to-ascii.svg)](https://travis-ci.org/npmdoc/node-npmdoc-image-to-ascii)

#### A Node.JS module that converts images to ASCII art.

[![NPM](https://nodei.co/npm/image-to-ascii.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-to-ascii)

- [https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ionică Bizău",
        "url": "https://ionicabizau.net"
    },
    "blah": {
        "h_img": "http://i.imgur.com/pKydY5P.png",
        "ex_img": "http://i.imgur.com/Om8G7dZ.png",
        "installation": "Check out the [INSTALLATION.md](INSTALLATION.md) guide for more information.",
        "example": [
            {
                "p": "In order to run the 'webcam.sh' provided in the 'example' folder, you will also need streamer. The script uses streamer to make webcam pictures and converts them into ASCII art using the 'webcam.js'"
            },
            {
                "code": {
                    "language": "sh",
                    "content": [
                        "# Ubuntu",
                        "$ sudo apt-get install streamer"
                    ]
                }
            },
            {
                "p": "To run the script just use:"
            },
            {
                "code": {
                    "language": "sh",
                    "content": "sh webcam.sh"
                }
            }
        ],
        "cli": "image-to-ascii-cli"
    },
    "bugs": {
        "url": "https://github.com/IonicaBizau/image-to-ascii/issues"
    },
    "contributors": [
        {
            "name": "Eric Baer"
        },
        {
            "name": "ComFreek"
        },
        {
            "name": "Szabo Cristian"
        },
        {
            "name": "Aleen"
        }
    ],
    "dependencies": {
        "asciify-pixel-matrix": "^1.0.0",
        "compute-size": "^1.0.1",
        "image-parser": "^1.0.0",
        "imgpx": "^1.0.2",
        "one-by-one": "^3.1.0",
        "terminal-char-width": "^1.0.0",
        "ul": "^5.2.1"
    },
    "description": "A Node.JS module that converts images to ASCII art.",
    "devDependencies": {},
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "7f314330399f74ec8494dbdd06940d1ff71413f5",
        "tarball": "https://registry.npmjs.org/image-to-ascii/-/image-to-ascii-3.0.7.tgz"
    },
    "files": [
        "bin/",
        "app/",
        "lib/",
        "dist/",
        "src/",
        "scripts/",
        "resources/",
        "menu/",
        "cli.js",
        "index.js"
    ],
    "gitHead": "9272328d603e3baef89f2b00a97c413340989ca2",
    "homepage": "https://github.com/IonicaBizau/image-to-ascii",
    "keywords": [
        "ascii",
        "image",
        "png",
        "node"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "ionicabizau"
        }
    ],
    "name": "image-to-ascii",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/IonicaBizau/image-to-ascii.git"
    },
    "scripts": {
        "test": "node example/index.js"
    },
    "version": "3.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
