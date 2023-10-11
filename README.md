# pdf slide trimmer

Latex slide pdf have many redundant pages (each page make have multiple step of animation, and each step will take up one pdf page). This script will remove the redundant pages and make the pdf file smaller and better for review.

## Pre-requisite

- depends on 'pdftoppm', install pdftoppm on linux machine
- 'pip install PyPDF2==2.12.1'

## Usage

- clone this repo
- modify the path in trim.ipynb
    - 'pdf_path' (pdf file folder)
    - 'pgm_path' (temp file folder)
    - 'target_path' (trimmed file folder)
- run trim.ipynb
