# prebuilt-packages

AUR binary packages I built.

## Mediawiki2latex-bin

Upstream: https://sourceforge.net/projects/wb2pdf/

Statically linked, no dependency on Haskell packages.

Modifications:

* Added `HtmlParser` to `mediawiki2latex.cabal` in order that the package can be actually built.
* Changed fonts used (e.g. `cmunbx.ttf` to `cmunbx.otf`), modified the path specifed in conformity with the texlive packaging of archlinux.
