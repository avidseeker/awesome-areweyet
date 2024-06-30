---
title: Spreadsheets
date: 2024-06-29
---

A spreadsheet program that sucks less:
* Support for custom number of rows and columns. ([LO](https://ask.libreoffice.org/t/86321), [sc-im](https://github.com/andmarti1424/sc-im/issues/818))
* Vim as a spreadsheet editor: [Filter view](https://neovim.discourse.group/t/4070)
* [Issue commands by typing](https://bugs.documentfoundation.org/show_bug.cgi?id=153002): [Styling commands](https://bugs.documentfoundation.org/show_bug.cgi?id=153001)
* Easily imports from other formats: [html](https://bugs.documentfoundation.org/show_bug.cgi?id=152984), [MediaWiki](https://bugs.documentfoundation.org/show_bug.cgi?id=156691)
* [Reorder rows and columns](https://bugs.documentfoundation.org/show_bug.cgi?id=156695)
* [Alternative cell colors support](https://bugs.documentfoundation.org/show_bug.cgi?id=155907)
* [Clip cell wrapping](https://bugs.documentfoundation.org/show_bug.cgi?id=155800)

## Commandline implementation

### Filter views
Possible filter implementation: Say you got dates and comments of the
following files: buy.tsv, sell.tsv, rent.tsv. Then

```bash
cat buy.tsv sell.tsv rent.tsv | sort
```

Browsing each .tsv file is the equivalent of filter view. The combined output is
the default view.

Problem is: how to map it back? Map it back by appending the SHA1 hash of every
line (+ fname, line no., etc.) to its beginning. That will make mapping easier
and less error prone.
