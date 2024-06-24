
# tmux Example Configuration File

Universal tmux configuration files for multiple distros (SUSE, Debian, Ubuntu etc.)

Tested with x86_64, i686 and ARM64 architectures under Debian 10,11,12, Ubuntu, Zorin OS and openSUSE 15.x and SLES 15.x

Tmux, or terminal multiplexer, allows users to switch easily between several programs in one terminal, detach them (they keep running in the background), and reattach them to a different terminal. This functionality is particularly useful when managing servers or conducting long-running processes that require persistence across sessions.

## Installation

````bash
cp tmux.conf  ~/.tmux.conf
tmux
````

## Features

- Nice status line
- Right click context menu (if mouse support is loaded/graphic terminal)
- multiple windows/screens (Ctrl-B 1..9)
- horizontal and vertical window split
- mouse support

## Screenshots

Example 1
![Example 1](tmux_osl153-example.png)

Example 2
![Example 2](tmux_osl154-example.png)

<!--
$Id: README.md,v 1.4 2024/06/06 14:44:45 ralph Exp $
vim:set fileencoding=utf8 fileformat=unix filetype=gfm tabstop=2 expandtab:
 -->
