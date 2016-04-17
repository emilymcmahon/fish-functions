# fish-functions
This is a collection of Fish (__F__riendly __I__nteractive __Sh__ell) functions
and aliases that I use. Please clone this repository and add your own functions.If you think your function might be useful to others, please submit a pull request!

## Included Functions
- `goto`: alias for `cd <dir>; pwd; ls`.
- `is`: usage: `is <command>`. Prints the exit status of the command.
- `lsd`: Lists subdirectories.
- `ok`: Clears the terminal and displays the current directory and its contents.
- `new`: Opens a new terminal window. Alias for `x-terminal-emulator`.

## Installation
Fish reads functions `~/.config/fish/functions`. Any `.fish` file there can be
executed immediantely and will highlight to dark blue like a regular command.
I recommend backing up and replacing your `~/.config/fish/functions` (if you
have one) with a symlink that points here. Then all changes and new functions 
become immediately available and `funcsave` will add the new function to your
clone or fork of this repository. Fish is smart and will only make `.fish`
files in into commands.
