# Project Name: EPUB Footnote Enhancer

This is a Python script for processing footnotes in EPUB e-books. It converts footnotes into popup footnotes and optionally adds a link to jump back to the footnote reference.

## Usage

1. Install the dependencies: `pip install -r requirements.txt`
2. Run the script: `python footnote_v2.py <epub_file_path> [--need_jump]`

Here, `<epub_file_path>` is the path to the EPUB file to be processed, and `--need_jump` is an optional argument. If provided, a link will be added in the footnote to jump back to the footnote reference.

## Notes

- This script assumes that footnotes are represented in HTML with `<a class="footnote">` tags. If your EPUB file uses a different markup, you may need to modify the script to suit your needs.
- This script modifies the original EPUB file. It is recommended to back up your EPUB file before running the script.