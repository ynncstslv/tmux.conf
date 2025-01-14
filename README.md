# .tmux.conf

This repository contains my custom Tmux configuration file (`.tmux.conf`), tailored to improve efficiency and usability for managing terminal sessions.

## Overview

Tmux is a terminal multiplexer that enables you to manage multiple terminal windows, panes, and sessions efficiently. It is an indispensable tool for multitasking in the command-line environment. This simple, yet effective, custom configuration includes optimized keybindings, styling, and quality-of-life enhancements for better performance.

## Installation

1. Install Tmux:

```bash
sudo apt update && sudo apt upgrade
sudo apt install tmux
```

2. Clone this repository inside `~/`:

```bash
git clone https://github.com/ynncstslv/tmux.conf
```

3. Move the `tmux.conf` file inside the cloned repo into `/~`:

```bash
mv ~/tmux.conf/tmux.conf ~/
```

4. Rename `tmux.conf` to `.tmux.conf`.

5. Reload the Tmux configuration:

```bash
tmux source ~/.tmux.conf
```

## Notes

This configuration is tailored to my personal workflow but can be easily adapted for other use cases. Feel free to customize it to fit your needs.
