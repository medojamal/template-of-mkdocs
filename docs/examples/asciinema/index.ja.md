# asciinema

Asciinema official documents.

- <https://docs.asciinema.org/>
- <https://github.com/asciinema/asciinema>

## Remote file

<style>
.asciicast {
    max-width: 600px;
}
</style>
<script async id="asciicast-569727" src="https://asciinema.org/a/569727.js"></script>

Add custom css like below to adjust terminal size.

```css
.asciicast {
    max-width: 600px;
}
```

## Local file

Use asciinema player.

- <https://docs.asciinema.org/getting-started/>
- <https://github.com/asciinema/asciinema-player/releases>

**Note: this cannot be used with i18n otherwise `demo.cast` and `demo.<lang>.cast` are prepared.**

<div id="demo" style="max-width: 600px;"></div>
<script>
document.addEventListener("DOMContentLoaded", function () {
  AsciinemaPlayer.create('demo.cast', document.getElementById('demo'), {
    speed: 2,
    idleTimeLimit: 2,
    autoPlay: true,
    loop: true,
    cols: 80,
    rows: 24,
  });
});
</script>

## Gif

Follow the <https://docs.asciinema.org/manual/agg/> to create gif.

This demo was created by the command `agg --theme monokai --cols 80 --rows=24 demo.cast demo.gif`.

![demo.gif](./demo.gif){ style="max-width:600px;" }
