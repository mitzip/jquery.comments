jquery.comments
===============

A jQuery plugin to work with HTML comments

## How To Use

Grab all comments in the DOM (that is all comments in page and accessible child iframes)
```javascript
$('*').comments();
```

Grab all the comments who are descendants of the body tag
```javascript
$('body').comments();
```

Grab all comments who are descendants of the body tag which can match a regular expression
```javascript
$('body').comments(/\d+/);
```

Get the string value of the first regular expression matching body tag descendant comment
```javascript
$('body').comments(/\d+/).get(0).nodeValue;
```
