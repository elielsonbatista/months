# months [![NPM version](https://img.shields.io/npm/v/months.svg?style=flat)](https://www.npmjs.com/package/months) [![NPM monthly downloads](https://img.shields.io/npm/dm/months.svg?style=flat)](https://npmjs.org/package/months)  [![NPM total downloads](https://img.shields.io/npm/dt/months.svg?style=flat)](https://npmjs.org/package/months) [![Linux Build Status](https://img.shields.io/travis/datetime/months.svg?style=flat&label=Travis)](https://travis-ci.org/datetime/months) 

> Months of the year.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [About](#about)

_(TOC generated by [verb](https://github.com/verbose/verb) using [markdown-toc](https://github.com/jonschlinkert/markdown-toc))_

## Install
Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save months
```

Install with [yarn](https://yarnpkg.com):

```sh
$ yarn add months
```

## Usage

```js
var months = require('months');

console.log(months);
//=> ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December']

console.log(months.abbr);
//=> ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec']

console.log(months.it);
//=> [ 'Gennaio', 'Febbraio', 'Marzo', 'Aprile', 'Maggio', 'Giugno', 'Luglio', 'Agosto', 'Settembre', 'Ottobre', 'Novembre', 'Dicembre' ]

console.log(months.abbr.it);
//=> [ 'Gen', 'Feb', 'Mar', 'Apr', 'Mag', 'Giu', 'Lug', 'Ago', 'Set', 'Ott', 'Nov', 'Dic' ]
```

## About
### Related projects
- [days](https://www.npmjs.com/package/days): Days of the week. | [homepage](https://github.com/jonschlinkert/days "Days of the week.")
- [nanoseconds](https://www.npmjs.com/package/nanoseconds): Convert the process.hrtime array to a single nanoseconds value. | [homepage](https://github.com/jonschlinkert/nanoseconds "Convert the process.hrtime array to a single nanoseconds value.")
- [o-clock](https://www.npmjs.com/package/o-clock): Simple javascript utility for displaying the time in 12-hour clock format. | [homepage](https://github.com/jonschlinkert/o-clock "Simple javascript utility for displaying the time in 12-hour clock format.")
- [pretty-time](https://www.npmjs.com/package/pretty-time): Easily format the time from node.js `process.hrtime`. Works with timescales ranging from weeks to nanoseconds. | [homepage](https://github.com/jonschlinkert/pretty-time "Easily format the time from node.js `process.hrtime`. Works with timescales ranging from weeks to nanoseconds.")
- [seconds](https://www.npmjs.com/package/seconds): Get the number of seconds for a minute, hour, day and week. | [homepage](https://github.com/jonschlinkert/seconds "Get the number of seconds for a minute, hour, day and week.")
- [time-stamp](https://www.npmjs.com/package/time-stamp): Get a formatted timestamp. | [homepage](https://github.com/jonschlinkert/time-stamp "Get a formatted timestamp.")
- [week](https://www.npmjs.com/package/week): Get the current week number. | [homepage](https://github.com/datetime/week "Get the current week number.")
- [year](https://www.npmjs.com/package/year): Simple utility to get the current year with 2 or 4 digits. | [homepage](https://github.com/jonschlinkert/year "Simple utility to get the current year with 2 or 4 digits.")

### Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Contributors
| **Commits** | **Contributor** |  
| --- | --- |  
| 11 | [jonschlinkert](https://github.com/jonschlinkert) |  
| 3  | [Rawnly](https://github.com/Rawnly) |  
| 1  | [doowb](https://github.com/doowb) |  

### Release history

### Building docs
_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

### Running tests

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

### Author
**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](https://twitter.com/jonschlinkert)

### License
Copyright © 2017, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on May 25, 2017._

