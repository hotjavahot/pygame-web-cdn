# My Pygame-web CDN

Self-hosted pygame-web assets extracted from `pygbag_archive_09.tar`.

## Files Included

- **pythons.js** - Main pygame-web loader
- **browserfs.min.js** - Browser filesystem support
- **cpython312/main.js** - Python 3.12 interpreter
- **vtx.js** - Terminal support
- **vt/** - Terminal assets (xterm.js, etc.)
- **empty.html** - Empty iframe page

## Usage

Replace the original pygame-web CDN URL:
```
https://pygame-web.github.io/archives/0.9/
```

With your self-hosted CDN:
```
https://YOUR_USERNAME.github.io/pygame-web-cdn/archives/0.9/
```

## Setup Complete

✅ Files extracted from local archive
✅ Proper directory structure created
✅ GitHub Pages deployment configured
✅ Ready for hosting

## Benefits

- No external dependencies
- Faster loading (GitHub's global CDN)
- Full version control
- Free hosting
- Custom domain support

## File Structure

```
archives/0.9/
├── pythons.js
├── browserfs.min.js
├── empty.html
├── vtx.js
├── cpython312/
│   └── main.js
└── vt/
    ├── xterm.css
    ├── xterm.js
    └── xterm-addon-*.js
```
