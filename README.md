<p align="center">
  <img src="kiro.jpg" alt="Kiro" width="220" />
</p>

# kiro-rofi

Erik's [rofi](https://github.com/davatorium/rofi) launcher config — a customised set of keybindings, theme references, and helper scripts dropped on top of vanilla rofi. Part of the `~/EDU/` learning series.

## What's in this repo

- `etc/skel/` — rofi user config (`config.rasi`, optional helper scripts) that lands in `/etc/skel/`.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Companion repo

- [kiro-rofi-themes](https://github.com/kirodubes/kiro-rofi-themes) — bundle of rofi themes (`*.rasi`) that pair with this config.

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S kiro-rofi
```

You'll also need rofi:

```bash
sudo pacman -S rofi
```

### Manual

```bash
git clone https://github.com/kirodubes/kiro-rofi.git
cd kiro-rofi
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

<!-- KIRO-FUNDING-FOOTER:START — managed by Kiro-HQ/cascade-readme-footer.sh -->
## Help fund Kiro

Everything I build here stays free and open — always. If Kiro or any of these
tools have ever saved you time or taught you something, a small monthly
contribution helps keep the work going. Donations target break-even, nothing
more — the core always stays free for everyone.

- GitHub Sponsors: https://github.com/sponsors/erikdubois
- Patreon: https://www.patreon.com/c/kiroproject
- YouTube memberships: https://www.youtube.com/@ErikDubois/join
- Ko-fi: https://ko-fi.com/erikdubois
- PayPal: https://www.paypal.me/erikdubois
<!-- KIRO-FUNDING-FOOTER:END -->

## License

See [LICENSE](./LICENSE).
