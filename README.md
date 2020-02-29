paper_tmpl
==========

This is how I write assignments for uni. Depends on Pandoc and PowerShell Core (not tested on Windows PowerShell). Optionally can use pandoc-citeproc.

The `panto` CLI tool offers the following commands:
* **`Build`** -- Compile any `.md` files into a PDF, using `pandoc-citeproc` to create citations if any .bib file is found. Use the `-open` switch to open the file when compilation is complete[^1]. Any remaining arguments will be forwarded to pandoc.
* **`Watch`** -- Run the `build` command if any file in the paper directory changes. Arguments same as `build`.

[^1]: Uses Atril as document viewer.

To do
-----
- [ ] Find a widely-available way to view a PDF.
