Resume

To compile, clone the repository and insure you have texlive installed.

pdflatex resume.tex

This produces a file with a blank page extra. I haven't figured out how in Latex
to change that, but you can always run 'pdftk' after the fact to remove a page.

pdftk resume.pdf cat 1 output resume-corrected.pdf
