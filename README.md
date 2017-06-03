Custom Build of Iosevka
=======================

This is my custom build of the [Iosevka](https://github.com/be5invis/Iosevka),
which has been my daily font since I found it.

Previously I used [Pragmata Pro](https://www.fsd.it/shop/fonts/pragmatapro/),
another great font that I was happy to pay for way back in 2007.

# Downloading

You can download the latest build [here](https://raw.githubusercontent.com/leonbreedt/iosevka-term-custom/master/dist/iosevka-term-custom-latest.zip).

# Building

If you want to build your own copy of this font, set up all the build tools as
described on the Iosevka README, then run:

```shell
$ make custom-config design='term v-zero-dotted v-tilde-low v-asterisk-low v-underscore-low v-at-short'
$ make custom
```

After a while, the built fonts will be in the `dist` folder.

# Sample

Example screenshot of my terminal ([Hyper](https://hyper.is)) using this font:

<img src="https://raw.githubusercontent.com/leonbreedt/iosevka-term-custom/master/Preview.png" alt="Preview" width="713" height="912">
