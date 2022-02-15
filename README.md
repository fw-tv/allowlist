# allowlist

Embed code:

```javascript
<fw-embed-feed
  channel="footokyo"
  playlist="gY84Oo"
  mode="row"
  open_in="default"
  max_videos="0"
  placement="middle"
  player_placement="bottom-right"
>
  <a href="https://fw-tv.github.io/allowlist/" target="_blank">
    Allow Firework for this website
  </a>
</fw-embed-feed>
```

Javascript popup:

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
