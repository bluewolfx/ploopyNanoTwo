# Ploopy Nano 2 Trackball Configuration

Custom QMK firmware configuration for the Ploopy Nano 2 Trackball.

**Last Updated:** 2026-01-05

## Features

- **Drag Scroll**: Click and hold button to enable scrolling mode
- **Inverted Scroll Direction**: Natural scroll (ball down = scroll down)

### Configuration Details

### Button Mapping
- Single button mapped to `DRAG_SCROLL`
- Click once to activate scroll mode
- Click again to deactivate scroll mode

### Scroll Direction
Inverted scroll direction enabled via `PLOOPY_DRAGSCROLL_INVERT`.
Toggle mode enabled by disabling `PLOOPY_DRAGSCROLL_MOMENTARY`.

## Directory Structure

```
ploopyNanoTwo/
├── README.md
├── nano2.json          # VIA configuration
└── custom_keymap/      # Keymap (symlinked to QMK firmware)
    ├── keymap.c
    └── config.h
```

## VIA Support

The nano2.json file provides VIA configuration for web-based keymap editing at usevia.app.

## Changelog

### 2026-01-05 - Toggle Mode Configuration
- Changed button behavior from hold to toggle mode
- Added inverted scroll direction
- Disabled PLOOPY_DRAGSCROLL_MOMENTARY for toggle functionality
- Set up symbolic link to QMK firmware structure
- Created VIA configuration file

