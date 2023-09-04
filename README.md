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

```sh
# mocha
bemenu-run --fb "#1e1e2e" --ff "#cdd6f4" --nb "#1e1e2e" --nf "#cdd6f4" --tb "#1e1e2e" --hb "#1e1e2e" --tf "#f38ba8" --hf "#f9e2af" --nf "#cdd6f4" --af "#cdd6f4" --ab "#1e1e2e"
```
```sh
# macchiato
bemenu-run --fb "#24273a" --ff "#cad3f5" --nb "#24273a" --nf "#cad3f5" --tb "#24273a" --hb "#24273a" --tf "#ed8796" --hf "#eed49f" --nf "#cad3f5" --af "#cad3f5" --ab "#24273a"
```
```sh
# frappe
bemenu-run --fb "#303446" --ff "#c6d0f5" --nb "#303446" --nf "#c6d0f5" --tb "#303446" --hb "#303446" --tf "#e78284" --hf "#e5c890" --nf "#c6d0f5" --af "#c6d0f5" --ab "#303446"
```
```sh
# latte
bemenu-run --fb "#eff1f5" --ff "#4c4f69" --nb "#eff1f5" --nf "#4c4f69" --tb "#eff1f5" --hb "#eff1f5" --tf "#d20f39" --hf "#df8e1d" --nf "#4c4f69" --af "#4c4f69" --ab "#eff1f5"
```

- Example for i3/sway config:
```sh
# mocha
set $menu bemenu-run --fb "#1e1e2e" --ff "#cdd6f4" --nb "#1e1e2e" --nf "#cdd6f4" --tb "#1e1e2e" --hb "#1e1e2e" --tf "#f38ba8" --hf "#f9e2af" --nf "#cdd6f4" --af "#cdd6f4" --ab "#1e1e2e"
bindsym $mod+d exec $menu
```
```sh
# macchiato
set $menu bemenu-run --fb "#24273a" --ff "#cad3f5" --nb "#24273a" --nf "#cad3f5" --tb "#24273a" --hb "#24273a" --tf "#ed8796" --hf "#eed49f" --nf "#cad3f5" --af "#cad3f5" --ab "#24273a"
bindsym $mod+d exec $menu
```
```sh
# frappe
set $menu bemenu-run --fb "#303446" --ff "#c6d0f5" --nb "#303446" --nf "#c6d0f5" --tb "#303446" --hb "#303446" --tf "#e78284" --hf "#e5c890" --nf "#c6d0f5" --af "#c6d0f5" --ab "#303446"
bindsym $mod+d exec $menu
```
```sh
# latte
set $menu bemenu-run --fb "#eff1f5" --ff "#4c4f69" --nb "#eff1f5" --nf "#4c4f69" --tb "#eff1f5" --hb "#eff1f5" --tf "#d20f39" --hf "#df8e1d" --nf "#4c4f69" --af "#4c4f69" --ab "#eff1f5"
bindsym $mod+d exec $menu
```

- You can also use an environment variable to set the theme:
```sh
# mocha
export BEMENU_OPTS='--fb "#1e1e2e" --ff "#cdd6f4" --nb "#1e1e2e" --nf "#cdd6f4" --tb "#1e1e2e" --hb "#1e1e2e" --tf "#f38ba8" --hf "#f9e2af" --nf "#cdd6f4" --af "#cdd6f4" --ab "#1e1e2e"'
```
```sh
# macchiato
export BEMENU_OPTS='--fb "#24273a" --ff "#cad3f5" --nb "#24273a" --nf "#cad3f5" --tb "#24273a" --hb "#24273a" --tf "#ed8796" --hf "#eed49f" --nf "#cad3f5" --af "#cad3f5" --ab "#24273a"'
```
```sh
# frappe
export BEMENU_OPTS='--fb "#303446" --ff "#c6d0f5" --nb "#303446" --nf "#c6d0f5" --tb "#303446" --hb "#303446" --tf "#e78284" --hf "#e5c890" --nf "#c6d0f5" --af "#c6d0f5" --ab "#303446"'
```
```sh
# latte
export BEMENU_OPTS='--fb "#eff1f5" --ff "#4c4f69" --nb "#eff1f5" --nf "#4c4f69" --tb "#eff1f5" --hb "#eff1f5" --tf "#d20f39" --hf "#df8e1d" --nf "#4c4f69" --af "#4c4f69" --ab "#eff1f5"'
```

## 💝 Thanks to

- [Iván Ruzo](https://github.com/iruzo)
- [Crony Akatsuki](https://github.com/cronyakatsuki)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2022-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
