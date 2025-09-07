## Version 0.6.3 September 7, 2025 (by Adit Vishnu)

- Update to run on Python 3, including:
  - Replacing `/` with `//` in for loops to ensure integer division
  - Switching to raw strings where appropriate (e.g., `r"\\"`)
- Minor: add background color support

## Version 0.6.2 May 6, 2009

- Additional support for accented characters
- Convert `>` and `<` to HTML codes
- Changed to handling of `\&` and `\%` in math mode to reflect different WordPress treatment of them

## Version 0.6.1 February 23, 2009

- Simplified format of `latex2wpstyle.py` (by Radu Grigore)
- Allow nesting of font styles such as `\bf` and `\em` (by Radu Grigore)
- Allow escaped symbols such as `\$` in math mode
- LaTeX macros are correctly "tokenized"
- Support `eqnarray*` environment

## Version 0.6 February 21, 2009

First release
