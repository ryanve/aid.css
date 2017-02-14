# aid.css
A11y utility module

## Setup
```
npm install aid.css --save
```

```
<link rel="stylesheet" href="node_modules/aid.css/aid.css">
```

## Example
```
<a href="#main" data-aid="hidden">skip</a>
```

## API

- <b>`[data-aid="hidden"]`</b> visually hidden, [based on H5BP](https://github.com/h5bp/html5-boilerplate/blob/5.3.0/src/css/main.css#L119-L133)
- <b>`[data-aid="focusable"]`</b> visually hidden but focusable, [based on H5BP](https://github.com/h5bp/html5-boilerplate/blob/5.3.0/src/css/main.css#L135-L149)
- <b>`[data-aid="visible"]`</b> forced visible

## Playground
[Try aid.css in your browser](http://ryanve.github.io/aid.css/)
