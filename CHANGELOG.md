# Changelog

This is a fork of https://github.com/richinseattle/newdraw

All notable changes to the original project will be documented in this file.


## 2019-10-03
### Added
- default filename in the save-dialog if `newdraw` was started with a filename argument
	or if the image was saved in between.
	Now, you just need to press <kbd>META-s</kbd> and <kbd>Enter</kbd> 
	for interim savings, which is more comfortable than entering a name every time.

### Changed
- program does not save to the `art`-directory anymore but to the original filepath.
  It creates a backup `filename~` with the old data, though.

### Removed
- the `art`-directory is obsolete now


