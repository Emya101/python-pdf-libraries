# Python PDF Library Exploration

A small educational notebook comparing **pypdf**, **pdfplumber**, and **PyMuPDF**. It also explores text/word bounding boxes, simple section extraction, regex phone matching, and OpenCV highlighting.

## Running it
```bash
pip install -r requirements.txt
jupyter notebook pdf_library_exploration.ipynb
```
Open the notebook and run the cells in order. This repository includes `sample_resume.pdf` with **entirely fictional information**. No personal resume or real phone number was republished.

## Demonstrated techniques
- Read PDF pages using different Python libraries
- Inspect spans and coordinates
- Clip a job experience section between headings
- Parse expected headings into a Python dictionary
- Find a phone number and draw its bounding box on a rendered PDF

## Notes
`PyPDF2` in the original exercise has been replaced by the maintained `pypdf` package. Heading matching and regex are intentionally simple; results vary with PDF structure, scanned text, and layout. The original notebook's saved outputs contained identifiable resume information and were removed.
