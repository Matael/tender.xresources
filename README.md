# Tender.Xresources - Color scheme based on tender.vim

This is the Xresources equivalent of @Jacoborus's [tender.vim](https://github.com/jacoborus/tender.vim).

## Getting Started

You can read about Xresources configurations in the [Arch Linux Wiki](https://wiki.archlinux.org/index.php/X_resources) or on [Wikipedia](https://en.wikipedia.org/wiki/X_resources).

#### Manual Installation
Copy the content of the [`tender`](https://github.com/Matael/tender.xresources/blob/master/src/tender) file into the `~/.Xresources` or `~/.Xdefaults` file and reload the settings with `xrdb`.

#### Via `#include`
Copy the [`tender`](https://github.com/Matael/tender.xresources/blob/master/src/tender) file to any place and import it via `#include "/path/to/tender"`.
A solution is to ``git clone`` this repo somewhere on your how and include it from there.
