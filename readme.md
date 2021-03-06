# Minimalist TUI Todo
Minimal todo list with simple and customizable UI in Linux terminal.

![screenshot](screenshot.jpeg)

## Features

- Minimal and customizable interface
- Fast task management with least possible key presses
- Import tasks from calcurse


## Instalation and running
Simply copy the _mintodo_ file into a directory with your binaries, for example into `home/user/.local/bin` 

Then, run by just typing `mintodo` in a linux terminal.

## Key bindings

`a` - add new task

`v` - mark task as done

`V` - mark all tasks as done

`i` - mark task as important

`i` - mark all tasks as important

`u` - unmark task

`U` - unmark all tasks

`e`,`c` - edit task

`d` - delete task

`D` - delete all tasks

`x` - import tasks from calcurse

`?` - toggle help

`q` - quit

## Configuration

On the first run, it will create a configuration file at `home/user/.config/mintodo/config.ini`

You can edit parameters and colors in the `config.ini` file. Here is an example config:

```
hint = a: Add · v (V): Done (all) · i (I): Important (all) · u (U): Unmark (all) · e: Edit · d (D): Delete (all) · ?: Help · q: Quit
folder_with_datafile = /home/r/.config/mintodo
calcurse_data_file = /home/r/.local/share/calcurse/todo
show_keybindings = Yes
use_unicode_icons = Yes
delete_confirmation = No
done_icon = ✔
todo_icon = •
important_icon = ‣
show_header = Yes
header = TODO LIST:

[Colors]
color_todo = 7
color_done = 6
color_title = 1
color_hints = 7
color_promts = 7
color_confirm = 1
color_important = 1
```
When configuring colors, numbers mean: 1 - red, 2 - green, 3 - yellow, 4 - blue, 5 - magenta, 6 - cyan, 7 - white

## Other programs
For similar minimalist terminal expirience, check out my [calendar](https://github.com/anufrievroman/minimalist-tui-calendar).
