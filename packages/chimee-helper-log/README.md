# chimee-helper-log

[![Build Status](https://img.shields.io/travis/Chimeejs/chimee-helper-log/master.svg?style=flat-square)](https://travis-ci.org/Chimeejs/chimee-helper-log.svg?branch=master)
[![Coverage Status](https://img.shields.io/coveralls/Chimeejs/chimee-helper-log/master.svg?style=flat-square)](https://coveralls.io/github/Chimeejs/chimee-helper-log?branch=master)
[![npm](https://img.shields.io/npm/v/chimee-helper-log.svg?colorB=brightgreen&style=flat-square)](https://www.npmjs.com/package/chimee-helper-log)
[![dependency Status](https://david-dm.org/Chimeejs/chimee-helper-log.svg)](https://david-dm.org/Chimeejs/chimee-helper-log)
[![devDependency Status](https://david-dm.org/Chimeejs/chimee-helper-log/dev-status.svg)](https://david-dm.org/Chimeejs/chimee-helper-log?type=dev) [![Greenkeeper badge](https://badges.greenkeeper.io/Chimeejs/chimee-helper-log.svg)](https://greenkeeper.io/)

logger of chimee

## get started

```shell
npm install chimee-helper-log --save
```

if you are using `flow`, you should import our flow defination, by adding this to your `.flowconfig`.

```
[ignore]

[include]

[libs]
./node_modules/chimee-helper-log/lib/index.flow.js
[options]

[lints]
```


## doc

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Log

[src/index.js:14-106](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L14-L106 "Source code on GitHub")

Log Object

#### GLOBAL_TAG

[src/index.js:25-25](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L25-L25 "Source code on GitHub")

Type: [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

#### FORCE_GLOBAL_TAG

[src/index.js:29-29](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L29-L29 "Source code on GitHub")

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

#### ENABLE_ERROR

[src/index.js:33-33](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L33-L33 "Source code on GitHub")

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

#### ENABLE_INFO

[src/index.js:37-37](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L37-L37 "Source code on GitHub")

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

#### ENABLE_WARN

[src/index.js:41-41](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L41-L41 "Source code on GitHub")

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

#### ENABLE_DEBUG

[src/index.js:45-45](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L45-L45 "Source code on GitHub")

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

#### ENABLE_VERBOSE

[src/index.js:49-49](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L49-L49 "Source code on GitHub")

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

#### error

[src/index.js:55-61](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L55-L61 "Source code on GitHub")

equal to console.error, output `[${tag}] > {$msg}`

**Parameters**

-   `tag` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** optional, the header of log
-   `msg` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** the message

#### info

[src/index.js:67-72](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L67-L72 "Source code on GitHub")

equal to console.info, output `[${tag}] > {$msg}`

**Parameters**

-   `tag` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** optional, the header of log
-   `msg` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** the message

#### warn

[src/index.js:78-83](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L78-L83 "Source code on GitHub")

equal to console.warn, output `[${tag}] > {$msg}`

**Parameters**

-   `tag` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** optional, the header of log
-   `msg` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** the message

#### debug

[src/index.js:89-94](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L89-L94 "Source code on GitHub")

equal to console.debug, output `[${tag}] > {$msg}`

**Parameters**

-   `tag` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** optional, the header of log
-   `msg` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** the message

#### verbose

[src/index.js:100-105](https://github.com/Chimeejs/chimee-helper-log/blob/387d837870c2a15a39eaeb09314870f4068c2d98/src/index.js#L100-L105 "Source code on GitHub")

equal to console.verbose, output `[${tag}] > {$msg}`

**Parameters**

-   `tag` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** optional, the header of log
-   `msg` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** the message