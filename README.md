#Angular 1.x wrapper for clamp.js

## What is it?
A simple to use Angular directive for truncating text. Allows multi-line truncation and displays an ellipsis at the end of the visible text.

## Usage
1. add the "ng-clamp" module as dependency to your angular app
2. decorate any element you want to clamp with a `clamp` attribute, specifying the number of lines it should be clamped to, e.g: `<div clamp="1"> {{ youVeryLongTextHere }}</div>`
3. enjoy your truncated text.

## License
MIT

## Want to help?
+ Contact the author at <david@pertiller.net> or visit [www.pertiller.net](https://www.pertiller.net).


## Changelog
* v1.1.4:
    * fixed issue in IE when assigning default configuration
* v1.1.3:
    * update bower.json
* v1.1.2:
    + add URL for issue tracking
* v1.1.1:
    + vendor prefixes for hyphening
* v1.1.0:
    + preventing overflow of long words or URLs by inserting a break with a hyphen
* v1.0.7:
    + changed package name to ng-clamp1 and published to npm
* v1.0.6:
    + to provide better readability, the element's title attribute is set with the (unclamped) innerText in case it doesn't have a title already
* v1.0.5:
    + shorthand syntax for clamping using the clamp attribute (e.g. `<div ng-bind="$ctrl.text" clamp="2"></div>`)
* v1.0.4:
    * forked from https://github.com/vygis/ng-clamp
