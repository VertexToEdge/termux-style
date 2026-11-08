<!-- Links -->
[bmac]: https://www.buymeacoffee.com/adi1090x
[ko-fi]: https://ko-fi.com/adi1090x
[paypal]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=U3VK2SSVQWAPN
[patreon]: https://www.patreon.com/adi1090x

**`LAST Updated`** : `August 2023`

> Unmaintained : Due to Termux not working properly on new Android versions and also Termux not getting maintained properly.

---

# Termux Style

<p align="left">
  <img src="https://img.shields.io/badge/Maintained%3F-No-red?style=for-the-badge">
  <img src="https://img.shields.io/github/license/adi1090x/termux-style?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/adi1090x/termux-style?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/adi1090x/termux-style?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/adi1090x/termux-style?color=violet&style=for-the-badge">
</p>

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

![gif](images/main.gif) <br />

> **`termux-style` provides color-schemes and powerline-ready fonts to customize the appearance of the Termux terminal.**

### How to install

Follow the steps below - 

```bash
# Go to home dir - 
cd $HOME

# Clone this repository (use `gh repo clone adi1090x/termux-style` if you want to use the GitHub CLI)- 
git clone https://github.com/adi1090x/termux-style

# Change to termux-style dir -
cd termux-style

# To install it, run -
./install

# And follow the steps, it'll be installed on your system.
```

### Run

Run `termux-style` & select the right option -

```bash
$ termux-style

    ┌──────────────────────────────────────────────────┐
    │░▀█▀░█▀▀░█▀▄░█▄█░█░█░█░█░░░░░█▀▀░▀█▀░█░█░█░░░█▀▀░░│
    │░░█░░█▀▀░█▀▄░█░█░█░█░▄▀▄░▄▄▄░▀▀█░░█░░░█░░█░░░█▀▀░░│
    │░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀░░░░░▀▀▀░░▀░░░▀░░▀▀▀░▀▀▀░░│
    └──────────────────────────────────────────────────┘
    [*] By- Aditya Shakya // adi1090x

    [C] Colors (89)
    [F] Fonts (21)
    [R] Random
    [I] Import
    [A] About
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 90 popular color-schemes.
+ 21 powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### D2Coding Nerd Font

`D2Coding-Nerd-Font` is the regular-weight D2Coding ligature font
from [Nerd Fonts v3.5.1](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/D2Coding.zip)
(`D2KodingLigatureNerdFont-Regular.ttf`). It supports Korean and Nerd Fonts icons.
This variant preserves Korean characters at twice the width of Latin characters.
The Mono variant in this release gives Korean characters the same advance width
as Latin characters, which can cause stretched or overlapping Korean text in Termux.
After running `./install` (or reinstalling an existing installation), select it
from the **Fonts** menu in `termux-style`.

The font is licensed under the SIL Open Font License 1.1; see
[`licenses/D2Coding/OFL.txt`](licenses/D2Coding/OFL.txt).

### Use Import
```bash
    [Select Option]: 4

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties`) of the color-scheme.
<br />

### Previews

|Colorschemes|Fonts|
|--|--|
|![img](images/colors.gif)|![img](images/fonts.gif)|

|Import - URL|Import - Local|
|--|--|
|![img](images/url.gif)|![img](images/local.gif)|

|Install|Uninstall|
|--|--|
|![img](images/install.gif)|![img](images/uninstall.png)|

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
