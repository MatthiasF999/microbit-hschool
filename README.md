# Rando 

Generate a random coordinate and display it on the LED screen. ``||input:on shake||``
 test.

```blocks
basic.forever(() => {
    led.toggle(randint(0, 4), randint(0, 4))
})
```

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
