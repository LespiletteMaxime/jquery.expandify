Expandify jQuery Plugin
================

Simple, light-weight, and feature-free jQuery plugin that expands and contracts textareas up to a certain height, based on newlines in the user's input.

**[jsFIDDLE DEMO](http://jsfiddle.net/mholt/dJWqN/)**

Usage
-----

Include jQuery on your page, then, when the document is ready:

```javascript
$('textarea').expandify(); 
```

You can also pass in a maximum number of rows (default is 5):

```javascript
$('#myTextarea').expandify(10);
```

That's it, folks!