## Using super-zaje to extract code from images

`zaje` is a syntax highlighter that aims to cover all your shell colouring needs. 
It can act as an ad-hoc replacement for cat and, with a spot of one-line shell functions tail and other friends.

I'm pleased to announce the release of `super-zaje` which can do everything `zaje` can but introduces one very useful enhancement: 
thanks to the magic of `tesseract` and [gosseract](https://github.com/otiai10/gosseract), `super-zaje` is able to extract text right off an image (both HTTP(s) URLs and local files are supported).

The slides in [super-zaje.pdf](./super-zaje.pdf) demonstrate its usefulness with a few sample LinkedIn posts that shared code as screenshots (a common case, alas, due to LI's inexplicable refusal to support `markdown`).

As an aside note, this presentation was written entirely in VIM and converted into a PDF using [mdtopdf](https://github.com/mandolyte/mdtopdf): a project by Cecil New, to which I've contributed syntax highlighting, powered by my [gohighlight project](https://github.com/jessp01/gohighlight), which `zaje` and `super-zaje` also leverage.
If you find yourself struggling to create similar presentations without using GUI tools, give it a go:)

### ASCIInema screencasts (Not videos!)

You can copy all text (commands, outputs, etc) straight off the player:)

[![super-zaje - extract and highlight text right off a remote image](https://asciinema.org/a/599719.svg)](https://asciinema.org/a/599719)

[![zaje - a colouriser to cover all your shell needs](https://asciinema.org/a/597732.svg)](https://asciinema.org/a/597732)

[![zaje - a colouriser to cover all your shell needs](https://asciinema.org/a/ltEfcN9sILkUFHruwQLn6rDXm.svg)](https://asciinema.org/a/ltEfcN9sILkUFHruwQLn6rDXm)

