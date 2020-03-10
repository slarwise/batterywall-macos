# Batterywall macos

Change background depending on the battery level and if charging. Currently five
different images are used depending on the battery level and these are cycled
when the battery is charging.

## Installation and usage

Clone this repository, i.e. `git clone
git@github.com:slarwise/batterywall-macos.git`. Then use `./batterywall-macos`
to start the script, use `Ctrl-C` to terminate. Add `&` to the start command to
run it in the background.

## Improvements

Currently the images are hardcoded, add command line options so that the user
can specify the directory in which to load images from.
