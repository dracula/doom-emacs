### [DOOM Emacs](https://github.com/hlissner/doom-emacs)

#### Installing theme

1. Open your `.doom.d/config.el`;
2. Add the following lines after the comments:
```lisp
;; There are two ways to load a theme. Both assume the theme is installed and
;; available. You can either set `doom-theme' or manually load a theme with the
;; `load-theme' function. This is the default:
(setq doom-theme 'doom-dracula) ;; << This line enables the theme
```

#### Activating theme

1. Press `M-x` and select `doom/reload` to apply the changes;
2. If changes doesn't apply, close and re-open the Emacs.
