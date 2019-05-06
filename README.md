#Natural Grid

Natural grid is a fully editable, simple, flex-box grids system written in scss.

## Getting started

### NPM install
First install natural-grid

``` 
$ npm i natural-grid --save
```

Import in your own project

``` 
@import '~/natural-grid/scss/natural-grid'
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


## Credits

Thanks for using Natural Grid

- **Author**    : Jim van Eijk
- **website**   : www.jimvaneijk.com
- **github**    : github.com/jimvaneijk
- **dribbble**  : dribbble.com/jimvaneijk
