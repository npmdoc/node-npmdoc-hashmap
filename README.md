# api documentation for  [hashmap (v2.0.6)](https://github.com/flesler/hashmap)  [![npm package](https://img.shields.io/npm/v/npmdoc-hashmap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hashmap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hashmap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hashmap)
#### HashMap Class for JavaScript

[![NPM](https://nodei.co/npm/hashmap.png?downloads=true)](https://www.npmjs.com/package/hashmap)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hashmap/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-hashmap_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hashmap/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hashmap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hashmap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ariel Flesler",
        "email": "aflesler@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/flesler/hashmap/issues"
    },
    "dependencies": {},
    "description": "HashMap Class for JavaScript",
    "devDependencies": {
        "chai": "3.5.0",
        "husky": "0.11.4",
        "jshint": "2.9.2",
        "mocha": "2.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e21f7aad2ad0d18775442ae0764766db28443b25",
        "tarball": "https://registry.npmjs.org/hashmap/-/hashmap-2.0.6.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "c361916e4c7f4f116aa6bd7cec2f79468a302cb6",
    "homepage": "https://github.com/flesler/hashmap",
    "keywords": [
        "hashmap",
        "map",
        "object",
        "array",
        "associative",
        "javascript",
        "nodejs",
        "node",
        "browser"
    ],
    "license": "MIT",
    "main": "./hashmap.js",
    "maintainers": [
        {
            "name": "flesler",
            "email": "aflesler@gmail.com"
        }
    ],
    "name": "hashmap",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/flesler/hashmap.git"
    },
    "scripts": {
        "precommit": "jshint hashmap.js",
        "prepush": "mocha test/ --reporter dot"
    },
    "version": "2.0.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module hashmap](#apidoc.module.hashmap)
1.  [function <span class="apidocSignatureSpan">hashmap.</span>HashMap (other)](#apidoc.element.hashmap.HashMap)
1.  number <span class="apidocSignatureSpan">hashmap.</span>uid



# <a name="apidoc.module.hashmap"></a>[module hashmap](#apidoc.module.hashmap)

#### <a name="apidoc.element.hashmap.HashMap"></a>[function <span class="apidocSignatureSpan">hashmap.</span>HashMap (other)](#apidoc.element.hashmap.HashMap)
- description and source-code
```javascript
function HashMap(other) {
		this.clear();
		switch (arguments.length) {
			case 0: break;
			case 1: this.copy(other); break;
			default: multi(this, arguments); break;
		}
	}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
