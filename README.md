# allowlist

```javascript
var e = (window.screen.width - 480) / 2,
  a = (window.screen.height - 400) / 2;
window.open(
  "https://fw-tv.github.io/allowlist/",
  "targetWindow",
  "toolbar=no,\n      location=no,\n      status=no,\n      menubar=no,\n      scrollbars=no,\n      resizable=no,\n      width="
    .concat(480, ",\n      height=")
    .concat(400, ",\n      left=")
    .concat(e, ",\n      top=")
    .concat(a)
);
```
