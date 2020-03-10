# Batterywall macos

Change background depending on the battery level and if charging. Currently five
different images are used depending on the battery level and these are cycled
when the battery is charging.

![Preview of battery charging animation](battery-charging.gif)

## Installation and usage

Clone this repository

```
git clone git@github.com:slarwise/batterywall-macos.git
```

Then run 

```
./batterywall-macos
```

to start the script, `Ctrl-C` to terminate. Add `&` to command to run it in the
background.

## Improvements

Currently the images are hardcoded, add command line options so that the user
can specify the directory in which to load images from.
