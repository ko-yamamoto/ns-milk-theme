# ns-milk-theme

my light theme


## Requirements

requires Emacs 24 or later

## Compatible types and colors

- rainbow-delimiters
- highlight-indentation
- auto-highlight-symbol
- moccur
- emacs-anzu
- skk
- org
- helm
- elscreen
- yalinum
- speebar
- eshell
- dired
- slime
- diff
- magit
- auto-complete

## Use

1.  Install this theme on your custom-theme-directory:

```lisp
;; set your custom-theme-directory
(setq custom-theme-directory "~/.emacs.d/themes/")
```

2. Load color theme

```lisp
;; on your settings
(load-theme 'ns-milk t)

;; or eval
(load-theme 'ns-milk)
```

## Screenshot

Basic colors (and auto-highlight-symbol)

![ns-milk](https://dl.dropboxusercontent.com/u/1517461/ns-milk.gif)
