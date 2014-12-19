# UltiSnips C snippets helping to write GObject code

## Installation

Those snippets use UltiSnips (
http://www.vim.org/scripts/script.php?script_id=2715 ) so you should install
and configure it first. I use Vundle ( https://github.com/gmarik/Vundle.vim )
to manage vim plugins but it's not mandatory.

If you use Vundle, you can just add to you ~/.vimrc

    Bundle 'thiblahute/gobject-snippets'

The content of this repo should be located in

    ~/.vim/UltiSnips

so you should have something like:

    ~/.vim/UltiSnips/c.snippets
    ~/.vim/UltiSnips/c

## Create a new GObject

To create a new GObject BadgerMushroom:
- create a new file *badger-mushroom.h* type **gheader** then the **Tab** key to generate the
object header
- create a new file *badger-mushroom.c* type **gobject** then the **Tab** key to generate the object code
