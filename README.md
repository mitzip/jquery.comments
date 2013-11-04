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

## License
Freely published into the Public Domain (see UNLICENSE file for more info)

## Author and Contributors
mitzip http://mitzip.com

## Contributing
Pull requests are welcome. I would ask that you add the following to your pull request description.

  I dedicate any and all copyright interest in this software to the
  public domain. I make this dedication for the benefit of the public at
  large and to the detriment of my heirs and successors. I intend this
  dedication to be an overt act of relinquishment in perpetuity of all
  present and future rights to this software under copyright law.

