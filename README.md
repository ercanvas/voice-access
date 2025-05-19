# Voice Access Minified Files

This folder contains the minified JavaScript and CSS files of the [voice-access](https://github.com/ercanvas/voice-access) project, which provides accessibility and voice command support.

## Files
- `voice-access.min.js`: Minified JavaScript file providing voice command and accessibility features.
- `voice-access.min.css`: Minified CSS file for the microphone button and its animations.

## Usage
You can directly include these files in your project via CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ercanvas/voice-access@main/minified-en/voice-access.min.css" />
<script src="https://cdn.jsdelivr.net/gh/ercanvas/voice-access@main/minified-en/voice-access.min.js" defer></script>
```

To add the microphone button:
```html
<button id="micBtn" aria-label="Microphone button">
  <i class="bi bi-mic-fill"></i>
  <span class="pulse"></span>
</button>
```

To customize commands, add this before the script:
```html
<script>
window.voiceCommands = {
  "profile": "/profile",
  "about": "/about",
  "home": "/"
};
</script>
```

For more information and documentation, see the [main repository](https://github.com/ercanvas/voice-access).
