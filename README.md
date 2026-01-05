# Ploopy Nano 2 Trackball Configuration

Custom QMK firmware configuration for the Ploopy Nano 2 Trackball.

**Last Updated:** 2026-01-05

## Features

- **Drag Scroll**: Click and hold button to enable scrolling mode
- **Inverted Scroll Direction**: Natural scroll (ball down = scroll down)

## Configuration Details

### Button Mapping
- Single button mapped to `DRAG_SCROLL`
- Click and hold to activate scroll mode
- Release to return to cursor mode

### Scroll Direction
Inverted scroll direction enabled via `PLOOPY_DRAGSCROLL_INVERT` in config.h.
Ball movement matches scroll direction.

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

### 2026-01-05 - Initial Configuration
- Created custom keymap with inverted scroll direction
- Added PLOOPY_DRAGSCROLL_INVERT configuration
- Set up symbolic link to QMK firmware structure
- Created VIA configuration file

