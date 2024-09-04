# Poetic HTML Alchemy

Poetic HTML Alchemy is a Python script that converts Markdown to HTML, supporting various Markdown extensions. This tool enhances Markdown conversion with features like code highlighting, table of contents generation, automatic line breaks, and wiki-style links.

## Features

- **Extensive Markdown Extension Support**: Maximizes Markdown's potential through a rich set of extensions including `extra`, `codehilite`, `sane_lists`, `toc`, `nl2br`, `smarty`, `attr_list`, `md_in_html`, and `wikilinks`.
- **User-Friendly Error Handling**: Provides clear error messages and resolution instructions, especially for non-UTF-8 encoded input files.
- **Straightforward Command-Line Interface**: Easily specify Markdown and HTML file paths using command-line arguments to execute the conversion process.

## Requirements

- Python 3.x
- Python-Markdown package

## Installation

This program requires Python 3.x and the Python-Markdown package. If you don't have Python installed, you can download it from the [official Python website](https://www.python.org/downloads/).

To install the required Python-Markdown package, run the following command:

```bash
pip install markdown
```

## Usage

Execute the following command in your terminal or command prompt:

```bash
python3 poetic_html_alchemy.py markdown <input_markdown_file_path> <output_html_file_path>
```

For example, to convert `example.md` to `example.html`, use:

```bash
python3 poetic_html_alchemy.py markdown example.md example.html
```

Note: The input file must have a `.md` extension, and the output file must have an `.html` extension. This will initiate the Markdown to HTML conversion process.

## Error Handling

If you encounter an encoding error, ensure that your input file is UTF-8 encoded. The script will provide a clear error message if this is not the case.