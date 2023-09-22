<h1 align="center">
		<br>
		<a href="https://plugins.jetbrains.com/plugin/21042">
				<img src="https://github.com/krios2146/intellij-theme-github/blob/main/src/main/resources/META-INF/pluginIcon.svg" width="300">
		</a>
	<br>
	CatHub Theme
</h1>

<div align="center">
	<img src="https://img.shields.io/github/actions/workflow/status/krios2146/intellij-theme-github/build.yml?style=for-the-badge&logo=github&labelColor=21262d&color=2ea043">
	<a href="https://plugins.jetbrains.com/plugin/21042"><img src="https://img.shields.io/jetbrains/plugin/v/21042?style=for-the-badge&color=2ea043&labelColor=21262d"></a>
	<a href="https://plugins.jetbrains.com/plugin/21042"><img src="https://img.shields.io/jetbrains/plugin/d/21042?style=for-the-badge&color=2ea043&labelColor=21262d"></a>
</div>

---

> Default version screenshot

![Screenshot](https://plugins.jetbrains.com/files/21042/screenshot_862a7f71-0164-4d36-923a-729b75764f49)

---

## Overview

<!-- Plugin description -->

This theme is my own interpretation of how a GitHub theme should look.  
It's a mix of one of the [Gerry Themes](https://plugins.jetbrains.com/plugin/18922-gerry-themes) and GitHub colors that I like the most.

Currently, the theme has three different versions:
- CatHub Preview: mimics GitHub.com file preview colorscheme
- CatHub VS Code: mimics VSCode GitHub Dark Default theme colorscheme
- CatHub: my own combination of both from the above

Important notes about CatHub Theme:
 - It's very dark and therefore high contrast
 - Mainly focusing on styling new IntelliJ IDEA UI and Java code
 - It may contain various bugs because it initially it was made for personal use
 - It's better to use CatHub VS Code variation with the [Rainbow Brackets
](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) plugin installed

<!-- Plugin description end -->

### Changes made to the original Gerry Themes

In particular to the `gerryDark.theme.json` file inside [this repository](https://github.com/gerryhjs/gerry-themes)

- Changed the color pallet
- Changed the checkbox styling
- Changed the button styling
- Changed the run widget styling

## Installation

- Using an IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "CatHub Theme"</kbd> >
  <kbd>Install Plugin</kbd>
  
- Manually:

  Download the [latest release](https://github.com/krios2146/intellij-theme-github/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
