# involve-tools-site

Built output for **tools.involve-consulting.com**.

`index.html` is generated. Do not edit it by hand — it is produced by `build.py`
in the private `involve-tools` repository, which inlines `assets/`, `data/` and
`tools/` into one self-contained file.

To publish a change: edit the source in `involve-tools`, run `python build.py`,
and copy `dist/index.html` here.

The page is genuinely self-contained: no fonts, analytics, trackers or images
are fetched from any other server. Everything the tools do runs in the
visitor's own browser and nothing they type leaves the page.

Programme data is sourced from each institution's own website, with the source
URL recorded on every record. Where a school does not publish a figure, the
tool says so rather than estimating.
