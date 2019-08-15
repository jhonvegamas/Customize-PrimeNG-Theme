# Customize-PrimeNG-Theme
Customize PrimeNG Theme

# Requirements

### Angular 7+

[![CircleCI](https://circleci.com/gh/angular/angular/tree/master.svg?style=shield)](https://circleci.com/gh/angular/workflows/angular/tree/master)
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=LzF3RzBVVGt6VWE2S0hHaC9uYllOZz09LS1BVjNTclBKV0x4eVRlcjA4QVY1M0N3PT0=--eb4ce8c8dc2c1c5b2b5352d473ee12a73ac20e06)](https://www.browserstack.com/automate/public-build/LzF3RzBVVGt6VWE2S0hHaC9uYllOZz09LS1BVjNTclBKV0x4eVRlcjA4QVY1M0N3PT0=--eb4ce8c8dc2c1c5b2b5352d473ee12a73ac20e06)
[![Join the chat at https://gitter.im/angular/angular](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/angular/angular?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![npm version](https://badge.fury.io/js/%40angular%2Fcore.svg)](https://www.npmjs.com/@angular/core)


Angular is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Join the chat at https://gitter.im/primefaces/primeng](https://badges.gitter.im/primefaces/primeng.svg)](https://gitter.im/primefaces/primeng?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![npm version](https://badge.fury.io/js/primeng.svg)](https://badge.fury.io/js/primeng)
[![Build Status](https://travis-ci.org/primefaces/primeng.svg?branch=master)](https://travis-ci.org/primefaces/primeng)

<a href="https://angular.io/"><img title="Angular" src="https://angular.io/assets/images/logos/angular/angular.svg" height="100"></a>


### PrimeNG V8

UI Components for Angular

See [PrimeNG homepage](http://www.primefaces.org/primeng) for live showcase and documentation.

See [PrimeNG on GitHub](https://github.com/primefaces/primeng)

<a href="https://www.primefaces.org/primeng/"><img title="PrimeNG" src="https://www.primefaces.org/wp-content/uploads/2018/05/primeng-sidebar.svg" height="100"></a>


# Instructions
1. Copy directory **nova-light** in **src/assets**
2. in **angular.json**
```JSON
    "styles": [
              "src/styles.css",
              "./node_modules/primeicons/primeicons.css",
              "src/assets/nova-light/theme.css",
              "./node_modules/primeng/resources/primeng.min.css"
            ],
```

3. in **src/assets/nova-light/colors.css** modify the colors

# Example:
  ```Stylus
  --v1: #107584;
  --v2: #0c5d69;
  --v3: #09464f;
  ```
