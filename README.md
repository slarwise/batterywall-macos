# Batterywall Macos

Change background depending on the battery level and if charging. Currently five
different images are used depending on the battery level and these are cycled
when the battery is charging. Animation when the battery is charging:

![Preview of battery charging animation](battery-charging.gif)


## Installation and usage

[Wallpaper](https://github.com/sindresorhus/macos-wallpaper) needs to be
installed. Then clone this repository with

```
git clone git@github.com:slarwise/batterywall-macos.git
```

To start the script, run

```
./batterywall-macos
```

Use `Ctrl-C` to terminate. Add `&` to the command to run it in the background.

## Improvements

Currently the images are hardcoded, we should add command line options so that
the user can specify the directory in which to load images from.
