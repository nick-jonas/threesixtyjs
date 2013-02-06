# threesixty

---

#### A jQuery plugin for generating a draggable 360 preview from an image sequence.

## Usage

```html
<div class="threesixty" data-path="assets/img/src/gem{index}.jpg" data-count="61">
```

The data-path attribute `assets/img/src/gem{index}.jpg` is the path to the image sequence.  The index being used to grab the images is 0-based and 1-digit.  The data-count attribute is the number of images.

```javascript
$(document).ready(function(){
    $('.threesixty').threeSixty({
        dragDirection: 'horizontal'
    });
});
```

The options for dragDirection are `horizontal` and `vertical`, horizontal being the default.


## In the Wild

[Example Site](http://nick-jonas.github.com/threesixtyjs)

