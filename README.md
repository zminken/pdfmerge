# pdfmerge
A command line utility coded in python to merge and split multiple pdfs.

Dependancies: 
    PyPDF2
    send2trash

usage: pdfmerge [-h] [-m | -x | -s] [-v] [-d DELIMITER] [-o OUTFILE]
                 filenamepages [filenamepages ...]

Merges, splits, and extracts pages from .pdf documents according to user specifications.


positional arguments:
  filenamepages         filename of input pdf with page numbers (optional) in
                        format filename::pages

optional arguments:
  -h, --help            show this help message and exit
  -m, --merge           merge two or more pdfs
  -x, --extract         extract specific pages from a pdf
  -s, --split           split the pdf into separate pages
  -v, --verbose
  -d DELIMITER, --delimiter DELIMITER
                        set delimiter between filename and page range.
                        defaults to '::'
  -o OUTFILE, --outfile OUTFILE
                        name of the output pdf file. Defaults to 'out.pdf'

Created by Zachary Minken
