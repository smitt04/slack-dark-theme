# Dark Theme for Slack 4+

This is a small script that applies a dark theme to slack. Slack 4+ required as they changed the internals in that version.

Thanks to [@caiceA](https://github.com/caiceA/slack-black-theme) for his work on the CSS portion of the theme.
Thanks to [@guyhalestorm](https://github.com/guyhalestorm) for his work on the windows section.

The issues were raised in https://github.com/widget-/slack-black-theme/issues/98 so I created a script to support osx, linux and windows.

### Install

1. Make sure to have a recent version of `nodejs` and `npm`
2. Install the asar package globally `npm i -g asar`
3. Download the `darkSlack.sh` and run `chmod u+x darkSlack.sh` to execute it.
4. Run `./darkSlack.sh` and refresh slack to enjoy the darkness.

5. You can revert slack to original by running `./darkSlack.sh --revert`

#### OSX and Linux

The script should just work without any issues, if you come accross any then let me know.

#### Windows Support

To use this script you need to install ubuntu or another linux distro as a windows subsystem for linux (WSL)
https://docs.microsoft.com/en-us/windows/wsl/install-win10
