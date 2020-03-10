# Batterywall Macos

Change desktop background depending on the battery level and if charging.
Currently five different images are used depending on the battery level and
these are cycled when the battery is charging. The desktop could look like this
when the battery is charging:

![Preview of battery charging animation](battery-charging.gif)


## Installation and usage

[Wallpaper](https://github.com/sindresorhus/macos-wallpaper) needs to be
installed. Then clone this repository with

```
git clone git@github.com:slarwise/batterywall-macos.git
```

To start the script, run

```
./batterywall-macos <img-prefix> <img-suffix>
```

in the cloned directory, or add the command to your `PATH`.

- `<img-prefix>`: The absolute path of the base image filename, e.g.
  `/Users/username/desktop-backgrounds/img`.
- `<img-suffix>`: The last part of the file, e.g. `.png`, `.jpg`.

The full filename for the image for 0-20% battery level should then be

```
<img-prefix>0<img-suffix>
```

and for 81-100%

```
<img-prefix>4<img-suffix>
```

So for the first set of images in the `imgs` folder we would have

- `<img-prefix>` = `/path/to/imgs/win95-gruvbox-bright-zoom-`
- `<img-suffix>` = `.png`

Use `Ctrl-C` to terminate the script and add `&` to the command to run it in the
background.

## Improvements

Simplify the way to specify images and if no arguments are given use some
defaults.
