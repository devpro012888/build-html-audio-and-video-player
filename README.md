# Build Html Audio and Video Player

A simple, accessible HTML audio and video player example. This repository contains a minimal demo (`index.html`) that demonstrates how to build custom audio and video controls using native HTML5 media elements, JavaScript, and CSS.

**Status:** Example/demo — open `index.html` in a browser to try it.

**Contents**
- `index.html`: The demo player and UI.

**Features**
- Custom play / pause controls for audio and video
- Seek bar and time display
- Volume control and mute toggle
- Responsive layout that works on desktop and mobile
- Accessibility-minded controls (keyboard focus, ARIA labels)

Getting started
----------------

Quick — open the demo in your default browser (no build step):

```sh
# macOS / Linux (double-click) — or open `index.html` from Finder
open index.html
```

If you prefer serving from a simple local HTTP server (recommended for media playback consistency):

```sh
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000 in your browser

# or with Node (http-server)
# npm install --global http-server
http-server -c-1 .
```

Usage
-----
- Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari).
- Use the visible controls to play/pause, seek, and change volume.
- Keyboard support: Tab to focus controls, Space/Enter to toggle play/pause.

Customization
-------------
- The demo uses plain HTML, CSS and JavaScript. Edit `index.html` to change styles or behavior.
- To add more media files, update the `<audio>` or `<video>` element `src` attributes in `index.html`.

Accessibility notes
-------------------
- Controls include ARIA attributes where appropriate; further improvements can be made for full screen reader support.
- Ensure any added controls remain keyboard-focusable and provide text alternatives.

Development notes
-----------------
- No build tools or dependencies are required — this is a static demo.
- If you add tooling, include a `package.json` or other manifest.

Contributing
------------
- Contributions are welcome: open an issue or submit a pull request.
- Keep changes small and focused; update this README if you add new files or features.

License
-------
This project is provided as-is. Add a license file if you want to explicitly define reuse terms.

Author
------
Created for educational/demo purposes.
