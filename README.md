gdate
===

gdate is date command written by golang

# Usage

```console
$ # Usage: gdate [-f FORMAT] [date]
$ gdate
2016-11-22 17:12:19 +0900  # Returns now (YYYY-MM-DD hh:mm:ss ZZZZ)
$ gdate -f YYYYMMDD
20161122  # Change format
$ gdate @1478745332
2016-11-10 11:35:32 +0900  ## Converts from unix time
```

# Installation

```console
$ go get github.com/b4b4r07/gdate
```

or

for zsh ([zplug](https://github.com/zplug/zplug)) users

```zsh
zplug "b4b4r07/gdate", \
    as:command, \
    from:gh-r
zplug install
zplug load
```

# License

MIT @ b4b4r07
