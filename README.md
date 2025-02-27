# Modern tmux Example Configuration File

Universal **tmux configuration file** for multiple distros (SUSE, Debian, Ubuntu, etc.).

Tested on x86_64, i686, and ARM64 architectures under Debian 10, 11, 12, Ubuntu, Zorin OS, and openSUSE/SLES 15.x.

Tmux is a powerful terminal multiplexer that lets you:
- Switch easily between multiple programs in one terminal.
- Detach sessions and let processes continue running in the background.
- Reattach to sessions from a different terminal, making it ideal for server management and long-running processes.

**Update 2025:** Requires a console/terminal that supports UTF8 characters. Hint, this may help along with a Console font that support UTF-8 ( I use "Hack Nerd Font Mono"):

    export LANG=en_US.UTF-8
    export LC_CTYPE=en_US.UTF-8


## Features

- **Dynamic Status Line:** Shows system load, uptime, and host information.
- **Context Menu:** Right-click support when using a graphical terminal with mouse support.
- **Multiple Windows:** Easily switch between screens (e.g., `Ctrl-B 1..9`).
- **Flexible Splits:** Supports both horizontal and vertical pane splits. (1,2,3,4,n windows etc.)
- **Mouse Integration:** Enhanced navigation and pane management with mouse support.

## Installation

Copy the [tmux.conf](tmux.conf) file to your home directory to use it as your default configuration:

```bash
cp tmux.conf ~/.tmux.conf
tmux
````

or if you just want to test this configuration file:

    tmux -f tmux.conf

## Screenshots

Example 1
![Example 1](tmux_osl153-example.png)

Example 2
![Example 2](tmux_osl154-example.png)

<!--
$Id: README.md,v 1.5 2025/02/25 23:54:10 ralph Exp $
vim:set fileencoding=utf8 fileformat=unix filetype=gfm tabstop=2 expandtab:
 -->
