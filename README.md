# Show Activities Overview Hot Corner

A GNOME Shell extension that toggles the activities overview when your mouse hits a configurable screen corner.

## Features

- Toggle the GNOME Activities overview by moving your mouse to any corner
- Configurable corner position via Extension Manager preferences (top-left, top-right, bottom-left, bottom-right)
- Defaults to top-left

**Note:** GNOME's built-in hot corner already triggers the overview from the top-left corner. This extension is most useful if you want the overview on a different corner, or if you have the built-in hot corner disabled.

## Installation

### From extensions.gnome.org (recommended)

Search for "Show Activities Overview Hot Corner" in [Extension Manager](https://flathub.org/apps/com.mattjakeman.ExtensionManager) or visit the extension page on [extensions.gnome.org](https://extensions.gnome.org).

### Manual

```bash
git clone https://github.com/jvjacq/show-activities-overview-hot-corner ~/.local/share/gnome-shell/extensions/show-activities-overview-hot-corner@jvjacq.com
glib-compile-schemas ~/.local/share/gnome-shell/extensions/show-activities-overview-hot-corner@jvjacq.com/schemas/
gnome-extensions enable show-activities-overview-hot-corner@jvjacq.com
```

## Supported GNOME versions

45, 46, 47, 48, 49, 50

## License

GPL-2.0
