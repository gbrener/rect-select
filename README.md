rect-select
===========

Rectangle selection and editing operations for Emacs. Akin to Vim's "Visual-Block Mode". This was written before Emacs v24.4, which ended up adopting CUA-mode's rectangle-mark mode.

## Motivation
* Marking a rectangular region visually before operating on it
* Typing in parallel
* Deleting in parallel
* Copying and pasting in parallel

## Installation
1. Place `rectangle-select.el` in your home directory, or any other directory on your Emacs load-path. To extend your load-path, add `(add-to-list 'load-path "path/to/rectangle-select.el")` to your .emacs file.
1. Add `(require 'rectangle-select)` to your `.emacs` file after `rectangle-select.el` is in your load-path.
1. Restart Emacs, or do an `M-x eval-buffer` while in your `.emacs` buffer.

## Usage
To enter `rectangle-select mode`:

`C-x <Spacebar>` - As you move your cursor, the rectangular region will appear.

While in `rectangle-select mode`:

Type! - it will be in parallel.

Delete! - it too, will be in parallel.

`C-w`, `C-y`, etc..

## Customize
`M-x customize` - search for "rect-select"
