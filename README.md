<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/Cloudef/bemenu">bemenu</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/template/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/bemenu?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/template/issues"><img src="https://img.shields.io/github/issues/catppuccin/bemenu?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/template/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/bemenu?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/bemenu/main/assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/bemenu/main/assets/bemenu-latte.png"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/bemenu/main/assets/bemenu-frappe.png"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/bemenu/main/assets/bemenu-macchiato.png"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/bemenu/main/assets/bemenu-mocha.png"/>
</details>

## Usage

- Launch from your wm, script or command bemenu adding the desired theme as params:
```
# mocha
bemenu-run -i -l 20 --fb "#1e1e2e" --ff "#94e2d5" --nb "#1e1e2e" --nf "#f5e0dc" --tb "#1e1e2e" --hb "#1e1e2e" --tf "#cba6f7" --hf "#89b4fa" --nf "#f5e0dc" --af "#f5e0dc" --ab "#1e1e2e"
# macchiato
bemenu-run -i -l 20 --fb "#24273a" --ff "#8bd5ca" --nb "#24273a" --nf "#f4dbd6" --tb "#24273a" --hb "#24273a" --tf "#c6a0f6" --hf "#8aadf4" --nf "#f4dbd6" --af "#f4dbd6" --ab "#24273a"
# frappe
bemenu-run -i -l 20 --fb "#303446" --ff "#81c8be" --nb "#303446" --nf "#f2d5cf" --tb "#303446" --hb "#303446" --tf "#ca9ee6" --hf "#8caaee" --nf "#f2d5cf" --af "#f2d5cf" --ab "#303446"
# latte
bemenu-run -i -l 20 --fb "#eff1f5" --ff "#179299" --nb "#eff1f5" --nf "#4c4f69" --tb "#eff1f5" --hb "#eff1f5" --tf "#8839ef" --hf "#fe640b" --nf "#4c4f69" --af "#4c4f69" --ab "#eff1f5"
```

- Example for i3/sway config:
```
# mocha
set $menu bemenu-run -i -l 20 --fb "#1e1e2e" --ff "#94e2d5" --nb "#1e1e2e" --nf "#f5e0dc" --tb "#1e1e2e" --hb "#1e1e2e" --tf "#cba6f7" --hf "#89b4fa" --nf "#f5e0dc" --af "#f5e0dc" --ab "#1e1e2e"
bindsym $mod+d exec $menu
```

- You can also use an environment variale to set the theme.
```
export BEMENU_OPTS='-i -l 20 --fb "#1e1e2e" --ff "#94e2d5" --nb "#1e1e2e" --nf "#f5e0dc" --tb "#1e1e2e" --hb "#1e1e2e" --tf "#cba6f7" --hf "#89b4fa" --nf "#f5e0dc" --af "#f5e0dc" --ab "#1e1e2e"'
```

## 💝 Thanks to

- [Iván Ruzo](https://github.com/iruzo)
- [Crony Akatsuki](https://github.com/cronyakatsuki)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
