# Kakoune Mint support

Plugin for [Kakoune][kakoune] text editor adding support for [Mint
language][mint]

![Screenshot](mint-screen.png)

## Features

- syntax highlighting
- basic code completion
- `mint-generate-procfile` command for use with Procfile managers like [Hivemind][hivemind]

Code completion is pretty basic, Mint has LSP implementation in the [roadmap](https://www.mint-lang.com/roadmap)
so there is no point in writing anything more advanced here.

## Installation

Source `mint.kak` from your `kakrc` or use some plugin manager.

[mint]: https://www.mint-lang.com/
[Kakoune]: http://kakoune.org/
[hivemind]: https://github.com/DarthSim/hivemind

## Changelog

- 0.1 2018-10-02:
    - initial release
    - Kakoune v2018.09.04
    - Mint 0.3.0

