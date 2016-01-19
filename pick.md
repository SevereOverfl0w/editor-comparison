<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Vim](#vim)
- [Emacs](#emacs)
- [LightTable](#lighttable)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# (Neo)Vim
Vim is a highly customizable text editor.

## Community

Vim's community is extremely tenacious. There's a
[subreddit](https://www.reddit.com/r/vim) on which you will find a number of
new plugins posted, and questions being asked.

Tired with Vim's slowdown in updates, the community has funded a group to fork
vim into neovim. Neovim has been focusing on a multitude of features which will
make the editor easier to work with. You can find these goals on their
[homepage](https://neovim.io/). Neovim has added a few apis, which some plugins
already take a look at, and are well worth looking at.

## Learning Curve

Vim has an editing system which you are unlikely to be familiar with from
previous editing experience. The concept is called "modal editing." In modal
editing, an editor like "Notepad" or Nano is always in "insert mode." Vim
extends this with some new modes. The concept can be initially quite difficult
to grasp, but once mastered and combined with text objects allows fast editing
of text.

Text objects are another important concept of vim. Let's take the word text
object. To move forward one word, whilst in normal mode, press `w`. A text
object can have a "motion" applied to it, for example `d` which is delete. To
delete a word, you chain these together `dw`. You can also move forward a
number of words, for example `5w` would move you forward 5 words. `5dw` deletes
5 words. This concept builds up far, and allows you to easily compose complex
changes to a file.

## Extensibility

Vim allows extension primarily through it's vimscript language. Whilst
considered a somewhat odd language, it has been used to great effect by a
number of plugin developers.

Vim comes with bindings for a number of languages, however vim has to be
compiled with support for those languages. Most distributions *do* include
those flags however. Neovim includes all interfaces by default, AND has come up
with a new way to work with other languages which haven't been embeddable up to
this point.
*(See [parinfer.js](https://github.com/snoe/nvim-parinfer.js) for a plugin using node.js
  and [deoplete](https://github.com/Shougo/deoplete.nvim) for python.)*

A huge number of options for plugins exist, and there are many competitors
within these for a choice of options (see: vim developers are tenacious) You're
unlikely to find plugins which extend beyond the scope of a text editor
however, vim developers tend to be very happy to switch to the command line for
many things, instead of adding it to their editor.

# Emacs
A small, lightweight editor.

# LightTable
An IDE.
