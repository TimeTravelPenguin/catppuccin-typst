<h2 align="center">🚧🚧🚧 THIS REPO IS CURRENTLY UNDER DEVELOPMENT 🚧🚧🚧</h2>

<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/catppuccin/typst">Typst</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/timetravelpenguin/typst/stargazers"><img src="https://img.shields.io/github/stars/timetravelpenguin/typst?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/timetravelpenguin/typst/issues"><img src="https://img.shields.io/github/issues/timetravelpenguin/typst?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/timetravelpenguin/typst/contributors"><img src="https://img.shields.io/github/contributors/timetravelpenguin/typst?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/timetravelpenguin/typst/main/assets/previews/catwalk_composite.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/timetravelpenguin/typst/main/assets/previews/latte.png"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/timetravelpenguin/typst/main/assets/previews/frappe.png"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/timetravelpenguin/typst/main/assets/previews/macchiato.png"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/timetravelpenguin/typst/main/assets/previews/mocha.png"/>
</details>

## Usage

Eventually, this package will be made available through typist's built-in package manager. For now, you can follow these steps:

1. Clone or download this repository.
2. Copy the `src` directory into the root of your Typst project. You may optionally rename the directory.
3. In your project, call
   ```typst
   #import "../src/lib.typ": catppuccin, themes
   #show: catppuccin.with(theme: themes.mocha)
   ```
   replacing `mocha` with the theme you want to use. You can also use the `catppuccin.with` function to customise the theme. See the documentation (todo!) for more information.

## TODO

- [ ] Investigate theming around plotting and visualisation
- [ ] Look into how to properly provide font(s) for the Jellee for headings. What should the body font be?
- [ ] Configure pretty math!
- [ ] Set up styles for numbers in the main text body (non-math). Requires regex testing ([see here](https://stackoverflow.com/a/12643073/10691106)).
- [ ] Make links more colourful
- [ ] Make references more colourful

## 💝 Thanks to

- [TimeTravelPenguin](https://github.com/TimeTravelPenguin)

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
