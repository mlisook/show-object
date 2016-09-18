# show-object

Displays a JSON formatted and highlighted object, mostly for demo pages and tutorials. A typical
use might be to demonstrate the result of an api call, AJAX, or the return value of a function.

## Live Demo

The [demo page for paper-input-place](https://mlisook.github.io/paper-input-place/) uses show-object
to demonstrate the return values.

## Install

Use bower to install the element:
```
bower install --save show-object
```

## Basic Use

To use the element just bind the object you want to show to the `showObject` property:
```HTML
<show-object show-object="[[myObject]]"></show-object>
```

## About / Credits

This element uses the JSON formatter from [umbrae/jsonlintdotcom](https://github.com/umbrae/jsonlintdotcom/blob/master/c/js/jsl.format.js) and the highlighting is done by
[highlightJS](https://highlightjs.org/).
