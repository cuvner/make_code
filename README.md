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
