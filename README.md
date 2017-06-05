
# aid.css = CSS accessibility classes with intent

## classes

### `.aid-say`

- visually hidden but screenreader voiceover accessible
- useful for providing spoken narration to voice listeners
- uses [H5BP technique](https://github.com/h5bp/html5-boilerplate/blob/5.3.0/src/css/main.css#L119-L133)

```html
<i class="aid-say">You rock!</i>
```

### `.aid-tab`
- visually hidden except shown as normal when focused
- useful for controls that you want visible when tabbed to

```html
<a href="#main" class="aid-tab">skip</a>
```

### `.aid-see`
- accessible background-image replacement technique
- useful for providing alternative text to background images or sprites
- uses `transparent` technique that affords text selection

```html
<a href="#edit" class="aid-see sprite sprite-edit">edit</a>
```

## aria

Favor `aria-label` [where supported](https://www.w3.org/TR/using-aria/#label-support) because it works without needing extra tags or CSS.

```html
<button aria-label="edit"><i class="icon icon-edit" aria-hidden="true"></i></button>
```

## setup

```
npm install aid.css
```

```css
@import "node_modules/aid.css/aid";
```

## contribute

[Please report bugs or share techniques](../../issues)
