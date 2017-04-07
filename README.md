# api documentation for  [sails-permissions (v2.2.0)](https://github.com/tjwebb/sails-permissions)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-permissions.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-permissions) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-permissions.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-permissions)
#### Comprehensive user permissions and entitlements system for sails.js and Waterline. Supports user authentication with passport.js, role-based permissioning, object ownership, and row-level security.

[![NPM](https://nodei.co/npm/sails-permissions.png?downloads=true)](https://www.npmjs.com/package/sails-permissions)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-permissions/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sails-permissions_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-permissions/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-permissions/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-permissions/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Webb",
        "email": "me@traviswebb.com"
    },
    "bugs": {
        "url": "https://github.com/tjwebb/sails-permissions/issues"
    },
    "bundleDependencies": [
        "fnv-plus",
        "lodash",
        "pluralize"
    ],
    "dependencies": {
        "fnv-plus": "^1.2.10",
        "lodash": "^3.10.0",
        "marlinspike": "^1.0",
        "pluralize": "^1.0.1",
        "sails-auth": "^2.0",
        "sails-generate-entities": "latest",
        "waterline-criteria": "^0.11.1"
    },
    "description": "Comprehensive user permissions and entitlements system for sails.js and Waterline. Supports user authentication with passport.js, role-based permissioning, object ownership, and row-level security.",
    "devDependencies": {
        "babel": "^5.8.21",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.2.1",
        "jshint": "^2.8.0",
        "mocha": "^2.x.x",
        "request": "^2.58.0",
        "sails": "github:balderdashy/sails",
        "sails-memory": "^0.10.5",
        "supertest": "^0.15.0",
        "waterline-postgresql": "^0.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "28544523a23ed21c9dd9a687bc3692c82714b829",
        "tarball": "https://registry.npmjs.org/sails-permissions/-/sails-permissions-2.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.10",
        "npm": ">= 2.3"
    },
    "gitHead": "850515a8b5789ae685fc5d8f13c82d84b50ce13d",
    "homepage": "https://github.com/tjwebb/sails-permissions",
    "keywords": [
        "sails",
        "sails.js",
        "permissions",
        "privileges",
        "entitlements",
        "access",
        "restriction",
        "passport",
        "grant",
        "roles",
        "security",
        "rbac",
        "acl",
        "enterprise",
        "audit",
        "trail",
        "tracking"
    ],
    "license": "MIT",
    "main": "dist/api/hooks/permissions/index.js",
    "maintainers": [
        {
            "name": "balderdash",
            "email": "hello@balderdash.io"
        },
        {
            "name": "ryanwilliamquinn",
            "email": "ryanwilliamquinn@gmail.com"
        },
        {
            "name": "sailsjs",
            "email": "sailsjs@balderdash.io"
        },
        {
            "name": "tjwebb",
            "email": "me@traviswebb.com"
        }
    ],
    "name": "sails-permissions",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tjwebb/sails-permissions.git"
    },
    "sails": {
        "isHook": true,
        "hookName": "permissions"
    },
    "scripts": {
        "prepublish": "gulp",
        "test": "gulp && mocha --reporter spec --compilers js:babel/register"
    },
    "version": "2.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sails-permissions](#apidoc.module.sails-permissions)
1.  object <span class="apidocSignatureSpan">sails-permissions.</span>generator

#### [module sails-permissions.generator](#apidoc.module.sails-permissions.generator)
1.  [function <span class="apidocSignatureSpan">sails-permissions.generator.</span>before (scope, next)](#apidoc.element.sails-permissions.generator.before)
1.  object <span class="apidocSignatureSpan">sails-permissions.generator.</span>targets
1.  string <span class="apidocSignatureSpan">sails-permissions.generator.</span>templatesDirectory



# <a name="apidoc.module.sails-permissions"></a>[module sails-permissions](#apidoc.module.sails-permissions)



# <a name="apidoc.module.sails-permissions.generator"></a>[module sails-permissions.generator](#apidoc.module.sails-permissions.generator)

#### <a name="apidoc.element.sails-permissions.generator.before"></a>[function <span class="apidocSignatureSpan">sails-permissions.generator.</span>before (scope, next)](#apidoc.element.sails-permissions.generator.before)
- description and source-code
```javascript
before = function (scope, next) {
  scope.module = options.module;
  scope.id = options.id;
  scope.createdAt = new Date();

  next();
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
