# ags

ags is a minimal tool that provides a summary of the repositories on
your system. ags aims to eliminate the need to navigate to each
repository root just to check for unstaged or uncommitted work.

### Documentation quick links
* [Install](#install)
* [Configuration](#configuration)
* [Uninstall](#uninstall)

![screenshot](https://raw.githubusercontent.com/wiki/nguyenvukhang/ags/images/screenshot.png)

### Install

To install, simply download the source and run the install script.

```
git clone https://github.com/nguyenvukhang/ags.git
cd ags && ./install
```

### Configuration

ags doesn't create the config file for you, but it looks for one at
`$HOME/.config/ags/scanlist`. This file should contain a list of paths
to the git repositories on your system, one path per line.

Here's what I used for the screenshot:
```
~/dots
~/dots/personal

~/repos/cal
~/repos/gcal
~/repos/min
~/repos/minnesoda
~/repos/notes

~/sunnus/app/main
~/sunnus/web/dev
```

### Uninstall

To uninstall, execute the install script with a `-d` flag.

```
./install -d
```