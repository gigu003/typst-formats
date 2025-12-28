# typst-formats

`typst-formats` repository contain a bunch of typst formats as the format of quarto extensions.

- `qsight-typst` : a typst format for blog post.
- `qcv-typst` : a typst format for Curriculum Vitae.
- `qcreport-typst` : a typst format for cancer registry report.
- `qcfact-typst` : a typst format for cancer fact sheet.
- `qcard-typst` : a typst format for slides.
- `letter-typst` : a typst format for Chinese style letter.
- `govdoc-typst` : a typst format for Government-issued documents of China.
- `card-typst` : a typst format for knowledge card.

## Installing

You can only install the clean version of extension without template `qmd` document using the following code in `terminal`:

```bash
quarto install extension gigu003/typst-formats/qcv
```

or you cancer install the extension with a template `qmd` document using the following code in `terminal`:

```bash
quarto use template gigu003/typst-formats/qcv
```