# Smart Edit

### Convert one text string to other by making smart edits

[See Demo](https://nicechay.github.io/smartEdit)

### Basic Usage

* Include `smartEdit.min.js` on your document's `<head>`

* Select html element preferrably paragraph containing text to be transformed
```javascript
var myElement = document.getElementById("myElementId");
```

* Initialization
```javascript
var xyz = new transformTo(myElement,"finalstring");
xyz.run(callback);
```
* The callback function runs after the transformation is complete

### Dependencies -> none


