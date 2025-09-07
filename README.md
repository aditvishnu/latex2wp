# LaTeX2WP

A fork of Luca Trevisan’s [LaTeX2WP](https://lucatrevisan.wordpress.com/latex-to-wordpress/).  
A tool that converts LaTeX documents into a format ready to paste into WordPress.

This version (0.6.3) updates the original for Python 3 compatibility.

## What’s New (0.6.3, September 7, 2025)

- Updated to run on Python 3
  - Replaced `/` with `//` in for loops to ensure integer division
  - Switched to raw strings where appropriate (e.g., `r"\\"`)

## Original Project

- Author: [Luca Trevisan](https://lucatrevisan.github.io/)
- Additional contributor: Radu Grigore
- License: [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html)

## Usage

`python3 latex2wp.py myfile.tex`

## Notes

- This fork is maintained for personal use but patches and feedback are welcome.
- See `changelog.md` for the full history (older entries preserved as in the original).
