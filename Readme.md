*This repository is a mirror of the [component](http://component.io) module [jaycetde/dom-contains](http://github.com/jaycetde/dom-contains). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jaycetde-dom-contains`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# DOM-contains

  Check if one DOM element contains another

## Installation

    $ component install JayceTDE/dom-contains

## Usage

```javascript

var domContains = require('dom-contains')
  , el1 = document.querySelector('#el1')
  , el2 = document.querySelector('#el2')
;

domContains(el1, el2); // true or false if el2 is a child of el1

```

## License

  MIT
