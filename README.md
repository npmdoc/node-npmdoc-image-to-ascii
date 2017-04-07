# api documentation for  [image-to-ascii (v3.0.7)](https://github.com/IonicaBizau/image-to-ascii)  [![npm package](https://img.shields.io/npm/v/npmdoc-image-to-ascii.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-image-to-ascii) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-image-to-ascii.svg)](https://travis-ci.org/npmdoc/node-npmdoc-image-to-ascii)
#### A Node.JS module that converts images to ASCII art.

[![NPM](https://nodei.co/npm/image-to-ascii.png?downloads=true)](https://www.npmjs.com/package/image-to-ascii)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-image-to-ascii%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-image-to-ascii/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ionică Bizău",
        "email": "bizauionica@gmail.com",
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
            "name": "Eric Baer",
            "email": "me@ericbaer.com"
        },
        {
            "name": "ComFreek",
            "email": "comfreek@outlook.com"
        },
        {
            "name": "Szabo Cristian"
        },
        {
            "name": "Aleen",
            "email": "aleen42@vip.qq.com"
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
            "name": "ionicabizau",
            "email": "bizauionica@yahoo.com"
        }
    ],
    "name": "image-to-ascii",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/IonicaBizau/image-to-ascii.git"
    },
    "scripts": {
        "test": "node example/index.js"
    },
    "version": "3.0.7"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module image-to-ascii](#apidoc.module.image-to-ascii)
1.  [function <span class="apidocSignatureSpan">image-to-ascii.</span>defaults.stringify_fn (pixels, options)](#apidoc.element.image-to-ascii.defaults.stringify_fn)
1.  object <span class="apidocSignatureSpan">image-to-ascii.</span>defaults

#### [module image-to-ascii.defaults](#apidoc.module.image-to-ascii.defaults)
1.  boolean <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>concat
1.  boolean <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>stringify
1.  [function <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>stringify_fn (pixels, options)](#apidoc.element.image-to-ascii.defaults.stringify_fn)
1.  object <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>size
1.  object <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>size_options

#### [module image-to-ascii.defaults.stringify_fn](#apidoc.module.image-to-ascii.defaults.stringify_fn)
1.  [function <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>stringify_fn (pixels, options)](#apidoc.element.image-to-ascii.defaults.stringify_fn.stringify_fn)
1.  [function <span class="apidocSignatureSpan">image-to-ascii.defaults.stringify_fn.</span>join (input)](#apidoc.element.image-to-ascii.defaults.stringify_fn.join)
1.  [function <span class="apidocSignatureSpan">image-to-ascii.defaults.stringify_fn.</span>stringify (input)](#apidoc.element.image-to-ascii.defaults.stringify_fn.stringify)
1.  [function <span class="apidocSignatureSpan">image-to-ascii.defaults.stringify_fn.</span>stringifyMatrix (input)](#apidoc.element.image-to-ascii.defaults.stringify_fn.stringifyMatrix)



# <a name="apidoc.module.image-to-ascii"></a>[module image-to-ascii](#apidoc.module.image-to-ascii)

#### <a name="apidoc.element.image-to-ascii.defaults.stringify_fn"></a>[function <span class="apidocSignatureSpan">image-to-ascii.</span>defaults.stringify_fn (pixels, options)](#apidoc.element.image-to-ascii.defaults.stringify_fn)
- description and source-code
```javascript
function asciifyMatrix(pixels, options) {
    var asciifier = new asciifyPixel.Asciifier(options);

    options = ul.merge(options, {
        stringify: true,
        concat: true
    });

    if (!Array.isArray(pixels)) {
        return [];
    }

    if (!Array.isArray(pixels[0])) {
        pixels = [pixels];
    }

    var result = pixels.map(function (row) {
        return row.map(function (p) {
            return asciifier.asciify(p);
        });
    });

    if (options.stringify !== false) {
        result = asciifyMatrix.stringify(result);
    }

    if (options.concat !== false) {
        result = asciifyMatrix.join(result);
    }

    return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.image-to-ascii.defaults"></a>[module image-to-ascii.defaults](#apidoc.module.image-to-ascii.defaults)

#### <a name="apidoc.element.image-to-ascii.defaults.stringify_fn"></a>[function <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>stringify_fn (pixels, options)](#apidoc.element.image-to-ascii.defaults.stringify_fn)
- description and source-code
```javascript
function asciifyMatrix(pixels, options) {
    var asciifier = new asciifyPixel.Asciifier(options);

    options = ul.merge(options, {
        stringify: true,
        concat: true
    });

    if (!Array.isArray(pixels)) {
        return [];
    }

    if (!Array.isArray(pixels[0])) {
        pixels = [pixels];
    }

    var result = pixels.map(function (row) {
        return row.map(function (p) {
            return asciifier.asciify(p);
        });
    });

    if (options.stringify !== false) {
        result = asciifyMatrix.stringify(result);
    }

    if (options.concat !== false) {
        result = asciifyMatrix.join(result);
    }

    return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.image-to-ascii.defaults.stringify_fn"></a>[module image-to-ascii.defaults.stringify_fn](#apidoc.module.image-to-ascii.defaults.stringify_fn)

#### <a name="apidoc.element.image-to-ascii.defaults.stringify_fn.stringify_fn"></a>[function <span class="apidocSignatureSpan">image-to-ascii.defaults.</span>stringify_fn (pixels, options)](#apidoc.element.image-to-ascii.defaults.stringify_fn.stringify_fn)
- description and source-code
```javascript
function asciifyMatrix(pixels, options) {
    var asciifier = new asciifyPixel.Asciifier(options);

    options = ul.merge(options, {
        stringify: true,
        concat: true
    });

    if (!Array.isArray(pixels)) {
        return [];
    }

    if (!Array.isArray(pixels[0])) {
        pixels = [pixels];
    }

    var result = pixels.map(function (row) {
        return row.map(function (p) {
            return asciifier.asciify(p);
        });
    });

    if (options.stringify !== false) {
        result = asciifyMatrix.stringify(result);
    }

    if (options.concat !== false) {
        result = asciifyMatrix.join(result);
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.image-to-ascii.defaults.stringify_fn.join"></a>[function <span class="apidocSignatureSpan">image-to-ascii.defaults.stringify_fn.</span>join (input)](#apidoc.element.image-to-ascii.defaults.stringify_fn.join)
- description and source-code
```javascript
function join(input) {
    return input.map(function (row) {
        return row.join("");
    }).join("\n");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.image-to-ascii.defaults.stringify_fn.stringify"></a>[function <span class="apidocSignatureSpan">image-to-ascii.defaults.stringify_fn.</span>stringify (input)](#apidoc.element.image-to-ascii.defaults.stringify_fn.stringify)
- description and source-code
```javascript
function stringify(input) {
    return input.map(function (row) {
        return row.map(function (c) {
            return c.toString();
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.image-to-ascii.defaults.stringify_fn.stringifyMatrix"></a>[function <span class="apidocSignatureSpan">image-to-ascii.defaults.stringify_fn.</span>stringifyMatrix (input)](#apidoc.element.image-to-ascii.defaults.stringify_fn.stringifyMatrix)
- description and source-code
```javascript
function stringifyMatrix(input) {
    return asciifyMatrix.join(asciifyMatrix.stringify(input));
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
