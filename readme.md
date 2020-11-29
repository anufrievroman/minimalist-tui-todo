# Minimalist TUI Todo
Minimal todo list with simple and customizable UI in linux terminal.

## Instalation and running
Simply copy the _mintodo_ file into a directory with your binaries, for example into `home/user/.local/bin` 

Then, run by just typing `mintodo` in a linux terminal.

## Key bindings

`a` - add new task

`v` - mark task as done

`u` - unmark tast as done

`e` - edit task

`d` - delete task

`D` - delete all tasks

`q` - quit

## Configuration

On the first run, it will create a configuration file at `home/user/.config/mintodo/config.ini`

You can edit parameters and colors in the `config.ini` file. Here is an example config:

```
[Parameters]
hint = a - add new • v - mark as done • u - unmark • d - delete • e - edit • D - delete all • q - quit
show_keybindings = Yes
delete_confirmation = No
done_icon = ✔
todo_icon = •
show_title = Yes
header = TODO LIST:

[Colors]
color_todo = 7
color_done = 6
color_title = 1
color_hints = 7
color_promts = 7
color_confirm = 1
```
When configuring colors, numbers mean: 1 - red, 2 - green, 3 - yellow, 4 - blue, 5 - magenta, 6 - cyan, 7 - white
