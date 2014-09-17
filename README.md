rect-select
===========

Rectangle selection and editing operations for Emacs. Akin to Vim's "Visual-Block Mode".

## Motivation
* Fucking "typing in parallel"... for the win.
* Delete in parallel too, while you're at it.
* Copy and paste in parallel, too?!
* I didn't know CUA-mode had a rectangle-mark mode. Have you seen the source-code for it, though? Mine is much cleaner and more concise.

## Installation
1. Place `rect-select.el` in your home directory, or any other directory on your Emacs load-path. To extend your load-path, add `(add-to-list 'load-path "path/to/rect-select.el")` to your .emacs file.
1. Add `(require 'rect-select)` to your `.emacs` file after `rect-select.el` is in your load-path.
1. Restart Emacs, or do an `M-x eval-buffer` while in your `.emacs` buffer.

## Usage
To enter `rect-select mode`:

`C-x <Spacebar>` - As you move your cursor, the rectangular region will appear.

While in `rect-select mode`:

Type! - it will be in parallel.

Delete! - it too, will be in parallel.

`C-w`, `C-y`, etc - you get the point.

## Customize
`M-x customize` - search for "rect-select". Customize away.

## Contribute
Start by forking the repo on GitHub:

https://github.com/gbrener/rect-select

1. Clone down your fork
1. Create a topic branch to house your changes
1. Make improvements
1. Change the README if necessary
1. Push your branch up to Github
1. Send a pull request for your branch
