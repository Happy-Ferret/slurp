# slurp

Select a region in a Wayland compositor and print it to the standard output.
Works well with [grim](https://github.com/emersion/grim).

It currently works on Sway 1.0 alpha.

## Building

Install dependencies:
* meson
* wayland
* cairo

Then run:

```shell
meson build
ninja -C build
build/slurp
```

## License

MIT
