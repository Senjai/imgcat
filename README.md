# imgcat

[![Build Status](https://travis-ci.org/eddieantonio/imgcat.svg?branch=master)](https://travis-ci.org/eddieantonio/imgcat)

It's like `cat` but for images.

![$imgcat cat.jpg](http://eddieantonio.ca/imgcat/assets/8dc8c1cde5.png)

# Install

On OS X:

```sh
brew tap eddieantonio/eddieantonio
brew install imgcat
```

For other platforms, see [Build](#Build).

# Usage

```sh
imgcat some_image.jpg
```

See the [manpage](./doc/imgcat.1.md) for more invocations.

# Build

```sh
make production=true
```

# Install

To install to `/usr/local`:

```sh
make install
```

To change the default prefix, simply provide `PREFIX=...`
to `make install`:

```sh
make install PREFIX=/opt
```

# Acknowledgements

 - Uses `stb_image` and `stb_image_resize` from [Sean T. Barrett's collection
   of public domain C libraries][stb].
 - 256 Color chart and data from Jason Milkin's [public domain chart][256svg].

[stb]: https://github.com/nothings/stb
[256svg]: https://gist.github.com/jasonm23/2868981

# License

2014, 2016 © Eddie Antonio Santos. See `LICENSE`.
