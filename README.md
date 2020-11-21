# WARNING

**Manjaro has updated to 5.20 now. you may be looking for** [the AUR package](https://aur.archlinux.org/packages/kwin-lowlatency/)**.**

# kwin-lowlatency-manjaro

this is a special PKGBUILD for Manjaro, which has ~~not updated Plasma to 5.19.~~ ~~5.20.~~ it just did.

## installation

you cannot use pamac yet, i think. I am not sure because I have never used Manjaro before.

in order to install this package, first clone this repository:

```
$ git clone https://github.com/tildearrow/kwin-lowlatency-manjaro
```

and then go to it:

```
$ cd kwin-lowlatency-manjaro
```

to build and install it, do:

```
$ makepkg -sri
```

## updating

to update the PKGBUILD, go to the directory where you have cloned this repo at, and then do:

```
$ git pull
```
