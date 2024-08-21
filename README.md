# Probhat Keyboard Layout for Mac OSX

This project provides the Probhat keyboard layout as a Mac OS native bundle. Probhat is one of the most popular keyboard layouts for the Bangla (aka Bengali) language.

This is faithful to the scheme published at [ekushey.org][e] <sup>[🏛][w]</sup> with two variations:

- **Probhat (BD)**: BDT symbol (৳) on <kbd>SHIFT</kbd>+<kbd>4</kbd>
- **Probhat (IN)**: INR symbol (₹) on <kbd>SHIFT</kbd>+<kbd>4</kbd>

⭐ *if this is useful to you, feel free to add a github star, thanks!* ⭐

## Install

### With Homebrew

Run this command to install:

```sh
brew install --cask bdeshi/taps/probhat-keyboard-layout
```

and this one to uninstall:

```sh
brew uninstall --cask bdeshi/taps/probhat-keyboard-layout
```

### Without Homebrew

Download and open a **source archive** of this project from the [Releases][r] page, and copy [`ProbhatKeyboardLayout.bundle`][p] to `~/Library/Keyboard Layouts/` (`~` means your home folder).

To uninstall, remove `ProbhatKeyboardLayout.bundle` from `~/Library/Keyboard Layouts/`.

## Usage

*These directions may differ slightly across Mac OS versions.*

Go to **System Settings > Keyboard**, add Probhat (BD) or Probhat (IN) in the **Input Sources** section.

Find or set the keyboard shortcut for cycling layouts in **System Settings > Keyboard > Keyboard Shortcuts > Input Sources**.

Layouts can be cycled from the menu bar as well by enabling the input menu item.

## Issues

Please report issues or feature requests on [github][s1] (or [gitea][s2]).

## Credits

- The Probhat layout was developed by ankurbangla.org.
- This Mac OS native keyboard layout bundle was generated with [Ukelele][k] (no guitars, sorry).

<hr>

## The Keyboard Layout

![graphical view of the layout](./probhat-layout-apple-wireless.png)
<sup>image generated with https://keyboard-layout-editor.com</sup>

[e]: https://www.ekushey.org/?page/probhat_layout
[w]: https://web.archive.org/web/20200815053905/https://ekushey.org/?page/probhat_layout
[r]: /bdeshi/probhat-mac-osx/releases
[p]: ProbhatKeyboardLayout.bundle
[s1]: https://github.com/bdeshi/probhat-mac-osx/issues
[s2]: https://git.bdeshi.space/bdeshi/probhat-mac-osx/issues
[k]: https://software.sil.org/ukelele/
