# Website of Techleague.io

## How to launch it

This website requires `Hugo` for building and running.

### Mac OS

```
brew install hugo
```

### Others

You can download the latest binary [here](https://github.com/gohugoio/hugo/releases) for your platform

```
git submodule update
hugo server
```

The website will be available at the following address http://localhost:1313

If you use 127.0.0.1:1313 you will run into CORS issues for the fonts, see [here](https://discourse.gohugo.io/t/dev-localhost-and-cors/4499/10) and [here](https://github.com/gohugoio/hugo/issues/1426)
