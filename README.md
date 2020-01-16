komputer maschine
======

komputer maschine is a shell script that gets your machine ready for development.

This script can be run once or as many times as you'd like. It installs everything that macOS needs to get to work.

## Requirements

* A komputer maschine
* macOS (>10.14)

## Install

```sh
curl --remote-name https://raw.githubusercontent.com/acolorbright/komputer-maschine/master/macos
sh macos 2>&1 | tee ~/komputer-maschine.log
```

## What You Get

**macOS tools:**

* [XCode Command Line Tools](https://developer.apple.com/xcode/downloads/) for developer essentials.
* [Homebrew](http://brew.sh/) for managing operating system libraries.

**Tools:**

* [git](https://git-scm.com/) for version control.
* [Vim](https://www.vim.org/) for a text editor in your console.
* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) to manage Heroku apps from the terminal.


**Programming languages and configuration:**

* [Node.js](http://nodejs.org/) and [npm](https://www.npmjs.org/) for running applications and installing JavaScript packages.
* [Python 3](https://github.com/sstephenson/rbenv) for an up-to-date Python install.

**Applications:**

* [1Password](https://1password.com/) as a secure password manager.
* [Alfred](https://www.alfredapp.com/) for increased productivity and efficiency with macOS.
* [Docker](https://www.docker.com/) for building, shipping and running applications.
* [Dropbox](https://www.dropbox.com/) for storing and sharing files.
* [Firefox](https://www.mozilla.org/de/firefox/developer/) for browsing the web and testing.
* [Google Chrome](https://www.google.com/chrome/) for browsing the web and testing.
* [Notion](https://notion.so/) to share knowledge with colleagues.
* [Slack](https://slack.com/) for more team communication and less email.
* [Spotify](https://www.spotify.com/) for music.
* [The Unarchiver](http://unarchiver.c3.cx/unarchiver) for extracting archives that are not supported by macOS out of the box.

## Debugging

The log of your script, successful or not, will be saved to `~/komputer-maschine.log`.

Read through it to see if you can debug the issue yourself.
If not, report where the script failed into a [new GitHub Issue](https://github.com/acolorbright/komputer-maschine/issues/new).

## Known Issues

Cask does not recognize applications installed outside of Homebrew Cask – in the case that the script fails, you can either remove the application from the install list or uninstall the application causing the failure and try again.

## License

© 2020 A Color Bright and licensed under the [MIT License](LICENSE).

## Credits and inspiration

Forked from https://github.com/heldinz/komputer-maschine which is heavily based on Lauren Dorman's [komputer maschine](https://github.com/laurendorman/komputer-maschine).
