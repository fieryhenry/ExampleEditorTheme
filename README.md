# Example Theme

This is an example repo for an external theme for my [Battle Cats Save Editor](https://github.com/fieryhenry/BCSFE-Python)

If you want to make your own theme for the editor, you can fork this repo and
edit the theme.json file to your liking.

If you need help, or want any extra features, you can join the [Discord
server](https://discord.gg/DvmMgvn5ZB) and ask in the `#tool-dev` channel, or
make suggestions in the `#suggestions` channel.

## How to make a theme

1. Fork this repo
1. Edit the `theme.json` file
1. Install [git](https://git-scm.com/downloads)
1. In the editor, go to `Edit config` -> `Theme` -> `Add Theme`
1. Enter the URL of your forked repo (with the `.git` at the end)
1. Restart the editor to see the changes

The theme will be added into the `external_themes` folder in `bcsfe` in your
documents folder. The folder name will be `ext-<author>-<short_name>` so that
collisions with other themes are avoided.
