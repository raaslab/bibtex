# bibtex

Bibtex files for papers

## Contents

1. refs.bib -- contains common bibliography of all references that can be used in any paper.

2. tokekar.bib -- contains only bib entries for Pratap Tokekar's papers. These are also contained in refs.bib

## Merging .bib files

### Use the bibtool (http://www.gerd-neugebauer.de/software/TeX/BibTool/en/)

> bibtool -s -d refs1.bib refs2.bib refs3.bib ... > refs\_merged.bib

### Use jabref
Simply copy paste references between files. After pasting make sure to find and remove duplicates using jabref tools.
