# ncspot-slackbuild

`ncspot` is now available at [slackbuilds.org](https://slackbuilds.org/repository/15.0/audio/ncspot/) for Slackware 15.0! This repository will remain up to track -current.

This is a SlackBuild for [Henrik Friedrichsen's ncspot](https://github.com/hrkfdn/ncspot) (version 0.10.1), an `ncurses` Spotify client written in `rust`. It is compatible with a full installation of Slackware -current as of July 31, 2022.

For Slackware 15.0, please use the files at [slackbuilds.org](https://slackbuilds.org/repository/15.0/audio/ncspot/).

**Sources**

Being a `rust`-based project, hundreds of "crates" are included among the sources. `source ncspot.info` and `wget $DOWNLOAD` simplify the task of downloading considerably! (This method does not work with zsh; use bash instead.)

**Dependencies**

`ueberzug` is an optional runtime dependency that is needed to display album art. To enable this feature, use `COVERS=yes ./ncspot.SlackBuild`. In addition, `ncspot` will not work without a premium Spotify account.
