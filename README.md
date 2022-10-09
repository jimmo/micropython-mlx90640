# micropython-mlx90640

Driver for MLX90640 IR Camera

I haven't written this driver yet, this is currently a demo for [micropython-lib#542](https://github.com/micropython/micropython-lib/pull/542).

It shows how to write a package.json, with URLs and dependencies, such that it can be installed from [mip](https://docs.micropython.org/en/latest/reference/packages.html#installing-packages-with-mip) via:

```
>>> import mip
>>> mip.install("github:jimmo/micropython-mlx90640")
```

Or from mpremote via

```bash
mpremote mip install github:jimmo/micropython-mlx90640
```
