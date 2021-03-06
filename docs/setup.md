Getting Started
===========

To get started with Drupdates you will need to install the script using the install
[instructions](index.md).  Once installed you will need to configure the [settings](settings.md)
using a local settings file.

The local settings file is a [YAML](http://en.wikipedia.org/wiki/YAML) file that is used to tell Drupdates how
to build out the various Drupal sites you are charged with maintaining.  You will
need to create the local settings file in your home directory in a hidden folder
title .drupdates, note: there is a period before the word drupdates, and title is settings.yaml

For Example:
$HOME/.drupdates/settings.yaml

Using a POSIX system the commands would look something like this (assuming your editor is vim)

```
$mkdir ~/.drupdates
$touch ~/drupdates/settings.yaml
$vim ~/drupdates/settings.yaml
```

This local settings file will override any settings that ship with Drupdates, the
order of precedence for settings can be found on the [settings documentation page](settings.md#overrides).

Sample Settings files can be found on the [settings documentation page](settings.md#samples)

Once you have a local settings file you will be able to run Drupdates simply by typing:

```
$drupdates
```
