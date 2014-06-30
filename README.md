# OS Inferno and Plan9 man pages backend for AsciiDoc

An [AsciiDoc](http://asciidoc.org/) plugin for generating
[OS Inferno](https://code.google.com/p/inferno-os/) and
[Plan9](http://plan9.bell-labs.com/plan9/) man pages (troff) from AsciiDoc
source.

To install the 9man plugin download
[9man.zip](https://github.com/powerman/asciidoc-9man-backend/releases/download/1.1.0/9man.zip)
and install it with `asciidoc`:

```
asciidoc --backend install 9man.zip
```

Usage:

```
asciidoc -d manpage -b 9man your_man_page.txt
```

Here is example man pages:
[register(1)](https://code.google.com/p/inferno-contrib-register/source/browse/doc/1/register.txt),
[tap(2)](https://code.google.com/p/inferno-contrib-tap/source/browse/doc/2/tap.txt).
