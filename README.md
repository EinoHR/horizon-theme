<p align="center">
  <a href="https://horizontheme.com/">
    <img alt="horizon banner" src="https://i.imgur.com/pwBUCSe.png">
  </a>
</p>

---

<p align="center">
  <!-- marketplace version -->
  <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">
    <img alt="marketplace version" src="https://img.shields.io/vscode-marketplace/v/jolaleye.horizon-theme-vscode.svg?maxAge=3600&style=for-the-badge&labelColor=1C1E26&color=F7B3A1">
  </a>
  <!-- downloads -->
  <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">
    <img alt="downloads" src="https://img.shields.io/visual-studio-marketplace/d/jolaleye.horizon-theme-vscode.svg?maxAge=3600&style=for-the-badge&labelColor=1C1E26&color=F7B3A1">
  </a>
  <!-- rating -->
  <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">
    <img alt="rating" src="https://img.shields.io/visual-studio-marketplace/stars/jolaleye.horizon-theme-vscode.svg?maxAge=86400&style=for-the-badge&labelColor=1C1E26&color=F7B3A1">
  </a>
</p>

<p align="center">
  <img alt="preview" src="https://raw.githubusercontent.com/jolaleye/horizon-theme-vscode/master/preview.png" width="90%">
</p>

### Visit [horizontheme.netlify.app](https://horizontheme.netlify.app/) for some nice previews and a color reference :)

# VSCode

## Installation

1. Open the **Extensions** sidebar in VS Code
2. Search for `Horizon Theme`
3. Click **Install**
4. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`
5. Select **Preferences: Color Theme** and choose a Horizon variant.
6. Enjoy! 🎉 Also, check out some of the personalization options below...

## Personalization

Tastes change all the time. Fortunately, VS Code makes it easy to customize just about every aspect of your editor.
If you want to change something, open the **Command Palette** and select **Preferences: Open Settings (JSON)**. Here, you can override VS Code's defaults or Horizon's colors.
Check out some of the personalization options below to customize Horizon to suit your taste.

_For more info on theming, visit the [Theme Authoring Guide](https://code.visualstudio.com/api/extension-capabilities/theming) and [Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)._

### Contrast

To add a border between sections of the editor, add the following to your settings...

```
"workbench.colorCustomizations": {
  "contrastBorder": "#16161C"
}
```

Or for Bright variants...

```
"workbench.colorCustomizations": {
  "contrastBorder": "#1A1C231A"
}
```

### Italics

The normal theme only uses italics in a few places. If you would prefer no italics at all, you can configure this in your settings...

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "No italics",
      "scope": ["comment", "markup.quote", "variable.language", "variable.parameter"],
      "settings": {
        "fontStyle": "normal"
      }
    }
  ]
}
```

### Tag Brackets `<>`

For gray rather than red brackets around HTML tags...

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "Tag brackets",
      "scope": ["punctuation.definition.tag"],
      "settings": {
        "foreground": "#BBBBBB"
      }
    }
  ]
}
```

# Userstyles

#### These only change colors

## Installation

  1. Install a userstyle manager like:
    [Stylus (Chrome)](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) [Stylus (Firefox)](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) [Stylus (Opera)](https://addons.opera.com/en-gb/extensions/details/stylus/) [Cascadea (Safari)](https://cascadea.app/)
  2. Open the raw .css file for the style in your browser.
  3. Click "Install style" to install the style
  4. Once installed, you will be redirected to editor page with the code for the theme loaded. Close this if you don't want or need to modify the style. 
  5. You're now done!


 ---

## Contributing

Check out the [contributing guide](CONTRIBUTING.md) to learn how you can report issues and help make changes.

Always be sure to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

[MIT](LICENSE) © [Jonathan Olaleye](https://github.com/jolaleye)

#### Credits for the original theme [Jonathan Olaleye](https://github.com/jolaleye) [Horizon Theme VSCode](https://github.com/jolaleye/horizon-theme-vscode)
