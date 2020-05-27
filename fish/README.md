# fish shell

## Install

1. install fish: `brew install fish`
2. install powerline: `pip3 install powerline-status`
3. move files and directories inside `.config/fish/` (add or update)
    1. [config.fish](./config.fish)
    2. [functions](./functions/)
    3. [completions](./completions/)

## Config

change default shell to fish: `sudo chsh -s (which fish)`. If you receive a message like `non-standard shell`, add fish path to `/etc/shells`: `sudo sh -c 'which fish >> /etc/shells'`

see `config.fish` file and `functions` and `completions` directories.
