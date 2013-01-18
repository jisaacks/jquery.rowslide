## jquery.rowslide

The jquery effect [slideUp](http://api.jquery.com/slideUp/) does not work on table rows. This plugin performs a slideUp on a table row, then removes the row and triggers a callback if one was passed.

### Usage

```javascript
// Remove all rows from table one at a time with sliding effect
removeAllRows = function() {
  $("table tr:first-child").rowslide(removeAllRows);
}
$(function(){
  removeAllRows();
});
```

### [Demo](http://jsfiddle.net/W48q9/)