## Requirements

- GTK `>=3.20`
- `gnome-themes-extra` (or `gnome-themes-standard`)
- `sassc` — build dependency

## Installation

### Manual Installation

Download black theme:

```sh
sudo bash install.sh -c dark -s standard -l --tweaks black rimless
```

### Uninstall theme

Uninstall legacy theme, run: `./install.sh -u`

Uninstall libadwaita theme, run: `./install.sh -u -l`

Uninstall gdm theme, run: `sudo ./install.sh -u -g`

> For more information, run: `./install.sh --help`
