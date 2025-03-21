---
title: Blinking LED
---

# 💡 Blinking LED Project (micro:bit)

This project toggles the center LED on and off every 500 milliseconds.

```blocks
basic.forever(function () {
    led.toggle(2, 2)
    basic.pause(500)
})
```

# Blinking LED Example

This is an example project that toggles the center LED on a micro:bit every 500 milliseconds using Microsoft MakeCode.

Below is the code:

```javascript
basic.forever(function () {
    led.toggle(2, 2)
    basic.pause(500)
})
```

<script src="https://makecode.com/gh-pages-embed.js"></script> 
<script> makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}"); </script>



---

Back to [Home](index.md)
