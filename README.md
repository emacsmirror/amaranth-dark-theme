[![MELPA](https://melpa.org/packages/amaranth-dark-theme-badge.svg)](https://melpa.org/#/amaranth-dark-theme)
# Amaranth Dark

[**Amaranth Dark**](https://melpa.org/#/amaranth-dark-theme) color theme for Emacs by **Emiliano Rizzonelli**. A dark background and high contrast theme.

# Screenshot #

![amarant-dark screenshot](./.github/assets/screenshot.png)

# Installation

### Package Manager

This theme is available in the [MELPA](https://melpa.org/#/) repository. Add this to your emacs config somewhere (.emacs, init.el, whatever...):

```
(require 'package)
(setq package-archives
      '(("melpa" . "https://melpa.org/packages/")))
(package-initialize)
```


And then run `M-x package-install RET amaranth-dark-theme RET` to install
the theme. Use `M-x customize-themes` to change your current theme.

### Manual Way

Download this repository locally with `git clone`: 

```
git clone git://github.com/a9sk/amaranth-dark-theme.git
```

Then add this to your emacs config somewhere (.emacs,
init.el, whatever...):

```
(add-to-list 'custom-theme-load-path
             "/path/to/amaranth-dark-theme/")
```

Use `M-x customize-themes` to change your current theme.
