# homebrew-portman

A [Homebrew](https://brew.sh) tap for [portman](https://github.com/meliharik/portman) — a native macOS menu bar app to view and terminate processes listening on TCP ports.

## Install

```sh
brew tap meliharik/portman
brew install --cask portman
```

To upgrade:

```sh
brew upgrade --cask portman
```

To uninstall (removes the app and its preferences):

```sh
brew uninstall --cask --zap portman
```

## What's in here

- [`Casks/portman.rb`](Casks/portman.rb) — the cask formula. Points at the latest signed DMG from [github.com/meliharik/portman/releases](https://github.com/meliharik/portman/releases).

## Reporting issues

For bugs in the **app**, open an issue in the [main portman repo](https://github.com/meliharik/portman/issues).

For issues with the **cask formula** (install/upgrade/uninstall failures), open an issue in this repository.

## License

The cask formula in this repository is released under the [MIT License](LICENSE), the same license as portman itself.
