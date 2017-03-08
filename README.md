#Angular 1.x wrapper for clamp.js

## Changelog
* v1.0.6:
    + to provide better readability, the element's title attribute is set with the (unclamped) innerText in case it doesn't have a title already
* v1.0.5:
    + shorthand syntax for clamping using the clamp attribute (e.g. `<div ng-bind="$ctrl.text" clamp="2"></div>`)