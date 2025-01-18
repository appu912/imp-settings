# This file has information about setting up .bashrc

## For Ubuntu

- Install a tool for copying and pasting contents of file.

  - `sudo apt update`
  - `sudo apt install xclip`

- Set an alias in your .bashrc file.

  - `alias pbcopy='xclip -selection clipboard'`
  - `alias pbpaste='xclip -selection clipboard -o'`
