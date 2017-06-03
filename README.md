# aid.css
a11y utility classes

## classes

### `.aid-hide`
- visually hidden but screenreader accessible
- [based on H5BP](https://github.com/h5bp/html5-boilerplate/blob/5.3.0/src/css/main.css#L119-L133)

```html
<legend class="aid-hide">Follow your heart.</legend>
```

### `.aid-tab`
- visually hidden like `.aid-hide` except shown as normal when focused
- useful for controls that you want visible when tabbed to

```html
<a href="#main" class="aid-tab">skip</a>
```

### `.aid-replace`
- accessible image replacement technique
- useful for providing alternative text to background images or sprites
- useful for providing alternative text to icons displayed via pseudocontent

```html
<a href="#main" class="aid-replace icon icon-edit">edit</a>
```

```html
<a href="#main" class="aid-replace sprite sprite-edit">edit</a>
```

## setup

```
npm install aid.css
```

```css
@import "node_modules/aid.css/aid";
```

## playground

[Try in your browser](http://ryanve.github.io/aid.css/)
