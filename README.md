<p align="center">
  <img src="kiro.jpg" alt="Kiro" width="220" />
</p>

# edu-rofi

Erik's [rofi](https://github.com/davatorium/rofi) launcher config — a customised set of keybindings, theme references, and helper scripts dropped on top of vanilla rofi. Part of the `~/EDU/` learning series.

## What's in this repo

- `etc/skel/` — rofi user config (`config.rasi`, optional helper scripts) that lands in `/etc/skel/`.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Companion repo

- [edu-rofi-themes](https://github.com/erikdubois/edu-rofi-themes) — bundle of rofi themes (`*.rasi`) that pair with this config.

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-rofi-git
```

You'll also need rofi:

```bash
sudo pacman -S rofi
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-rofi.git
cd edu-rofi
sudo cp -r etc/skel/. /etc/skel/
```

Existing users can pull the config into their own home:

```bash
cp -rT /etc/skel ~/
```

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
