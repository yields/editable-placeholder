
# editable-placeholder

  Editable placeholder.

## Installation

    $ component install yields/editable-placeholder

## Example

```html
<h1></h1>
<div></div>

<script>
  var placeholder = require('editable-placeholder')
    , div = document.querySelector('div')
    , h1 = document.querySelector('h1');

  div.contentEditable = true;
  h1.contentEditable = true;

  placeholder(h1, 'Type a title');
  placeholder(div, 'Type your post');
</script>
```


## License

  MIT
