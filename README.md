<h2 align="center"><img src="https://user-images.githubusercontent.com/2610287/236253542-ab75c56d-0bbc-457a-8587-d5d2c78d0eb3.svg" height="128"><br>Wakib Keybindings Project</h2>

Project page for the simple keybinding scheme Wakib. 

## Project Goals

The project was born from an attempt to come up with a keybindings scheme for cursor movement to replicate much of what Vim and Emacs bindings do but in a simpler manner. Initially this started off as an Emacs extension, but slowly grew to cover more programs. This is now a project to enable the use of these keybindings everywhere possible.

## Project Basics

The basic keybindings are shown below. These deal mainly with cursor movement and deleting, and so can be used with just about any program.

![Wakib-Basic](https://user-images.githubusercontent.com/2610287/236259599-b9bc895c-dc52-4ff3-93ee-32e2baed3b1f.png)

## Project Implimentation

### [QMK Keyboard](https://github.com/darkstego/qmk_firmware)

The gold standard for Wakib keybindings is implementing them at the keyboard level. This allows the use of these keybindings practically everywhere. Also, thanks to being able to destinguinsh between right and left ALT and Shift buttons, this implementation allows using ALT and Shift with the Wakib arrow keys as well as still being able to use the ALT button with the keys used as shortcuts. The Wakib keybindings can be copied to any QMK compatible keyboard.

### [Emacs](https://github.com/darkstego/wakib-keys)

The progenitor of the project. This is an implementation of these keybindings in Emacs, as an alternative to the Emacs and Vim bindings. Given how flexible Emacs is, this implementation has the most elaborate keybindings. There is also an [Emacs starter-kit](https://github.com/darkstego/wakib-emacs) with the same name that implements the keybindings and other basic features.

### [VSCode](https://github.com/darkstego/wakib-vscode-keybindings)

An implementation for VSCode. Not as elaborate as the Emacs implementation. But does provide the basic cursor movements that are most used in a text editor.

### [Bash (readline)](https://github.com/darkstego/wakib-readline)

For users of the Bash shell or other programs that use readline.

### [Zsh](https://github.com/darkstego/wakib-zsh)

For users of the shell Zsh.

### [Fish](https://github.com/darkstego/wakib-fish)

Support for the shell Fish.

### [Midnight Commander](https://github.com/darkstego/wakib-mc)

Shortcuts to use with Midnight Commander.
