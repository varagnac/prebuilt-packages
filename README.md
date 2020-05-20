# prebuilt-packages

AUR binary packages I built.

## Mediawiki2latex

Upstream: https://sourceforge.net/projects/wb2pdf/

Modifications:

* Added `HtmlParser` to `mediawiki2latex.cabal` in order that the package can be actually built.
* Changed fonts used (e.g. `cmunbx.ttf` to `cmunbx.otf`), modified the path specifed in conformity with the texlive packaging of archlinux.
