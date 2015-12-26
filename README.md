<p align="center">
  <a href="http://dev.stephendiehl.com/hask/">
    <img src="http://dev.stephendiehl.com/hask/img/title.png"/>
  </a>
</p>

[![MIT License](http://img.shields.io/badge/license-mit-blue.svg)](https://github.com/sdiehl/wiwinwlh/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/sdiehl/wiwinwlh?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Real Online:

* [**HTML**](http://dev.stephendiehl.com/hask/)

Contributing
------------

If you want to submit a fix for a typo or fix for code then just submit a pull
request, and I'm happy to recompile the resulting document.

If for some reason you want to compile the HTML page yourself, then you'll need
to compile the preprocessor against Pandoc and then run make to build the page.

```bash
$ make
$ firefox tutorial.html
```

Alternatively a PDF or EPUB file can be generated by one of the following
commands:

```bash
$ make tutorial.pdf
$ make tutorial.epub
```

Stack
-----

Alternatively using the stack build system:

```bash
$ stack ghc includes.hs -- -o includes 
$ stack exec make
$ firefox tutorial.html
```

License
-------

Stephen Diehl (2013-2016)

No rights reserved. The person who associated a work with this deed has dedicated the work to the public
domain by waiving all of his or her rights to the work worldwide under copyright law, including all related
and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking
permission.
