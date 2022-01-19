# ncspot-slackbuild

This is a SlackBuild for [Henrik Friedrichsen's ncspot](https://github.com/hrkfdn/ncspot) (version 0.9.5), an `ncurses` Spotify client written in `rust`. It is compatible with a full installation of Slackware -current as of January 19, 2022.

**Sources**

Being a `rust`-based project, hundreds of "crates" are included among the sources. `source ncspot.info` and `wget $DOWNLOAD` simplify the task of downloading considerably! (This method does not work with zsh; use bash instead.)

**Dependencies**

`ueberzug` is an optional runtime dependency that is needed to display album art. To enable this feature, use `COVERS=yes ./ncspot.SlackBuild`. In addition, `ncspot` will not work without a premium Spotify account.
