
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
