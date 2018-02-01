# Vim 8 packages directory

This directory contains packages loaded natively by Vim 8+.

## Autoload packages

Automatically-loaded ppackages go in the `start/` subdirectory and will be loaded when Vim starts (if plugin loading is enabled).

## Optional packages

Optional packages go in the `opt/` subdirectory and will only be loaded when requested via the `:packadd` command.

## Further reading

- [`:help packages`](http://vimhelp.appspot.com/repeat.txt.html#packages)