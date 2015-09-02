# LilyPond for Vim

This is a collection of scripts for working with [LilyPond][] using [Vim][].

It's mostly copied from the LilyPond source code, except:

* Because it's in a separate repository, you can use it with plugin management
  such as [Pathogen][] or [Vundle][]

* The indent script uses [banner indentation][], which I prefer to the ugly K&R
  style used in the original. It also handles braces opening and closing on the
  same line (e.g. `\layout {}`)

* The custom keybindings have been tweaked slightly: they use `xdg-open` instead
  of hard-coding the application name.

[LilyPond]: http://lilypond.org/
[Vim]: http://www.vim.org/
[Pathogen]: https://github.com/tpope/vim-pathogen
[Vundle]: https://github.com/VundleVim/Vundle.vim
[banner indentation]: https://en.wikipedia.org/wiki/Indent_style#Banner_style

## Credits

This is a fork from [here][1], which itself is a fork from [here][2] which is
mostly just a copy of the LilyPond source code put into a plugin for convenience.
The parent fork of this project wasn't accepting bugs or PR's so I decided just
to maintain my own fork of this project.

[1]: https://github.com/lfairy/lilyvim
[2]: https://github.com/gisraptor/vim-lilypond-integrator
