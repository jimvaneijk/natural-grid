# Natural Grid

Natural grid is a fully editable, simple, flex-box grids system written in scss.

## Getting started

### NPM install
First install natural-grid

``` 
$ npm i natural-grid --save
```

Import in your own project

``` 
@import '~natural-grid/scss/natural-grid'
```

### CDN load

**Comming soon**

``` 
<link rel="stylesheet" href="https://www.get-natural.com/grid/natural-grid.css">
```

*Uses the default settings (see below)*


## Change default settings

To change the default settings to your own settings. you will need to add the following variable

### breakpoints
``` 
$grid-breakpoints: (
    'small': 420px,
    'medium': 768px,
    'large': 1024px,
    'huge': 1600px,
);
```
### Gutter width
```
$grid-gutter: 32px;
```

### Column count
```
$grid-columns: 12;
```

## NEW Utilities

You can use simple utilities for spacing. 

### Margins
``` 
mt - margin-top
mr - margin-right
mb - margin-bottom
ml - margin-left

my - margin-top & margin-bottom
mx - margin-left & margin-right
```

### Padding
``` 
pt - padding-top
pr - padding-right
pb - padding-bottom
pl - padding-left

py - padding-top & padding-bottom
px - padding-left & padding-right
```

### Steps

Every spacer has his own size you can set them up like this:

```
$spacers: (
    0: 0,
    1: 0.25rem,
    2: 0.5rem,
    3: 1rem,
    4: 1.5rem,
    5: 3rem,
) !default;
```

All spacers have there own responsive option like: 

```
<div class="mr-small-1">
    Block with margin right wich is visable from small
</div> 

<div class="py-medium-4">
    Block with top and bottom padding wich is visable from medium
</div> 
```



## Credits

Thanks for using Natural Grid

- **Author**    : Jim van Eijk
- **website**   : www.jimvaneijk.com
- **github**    : github.com/jimvaneijk
- **dribbble**  : dribbble.com/jimvaneijk
