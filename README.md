# fdp

## Install deps
You might need more deps than this, I'm not sure. LaTeX does fetch its own CTAN dependencies though.
```bash
sudo apt-get install latexmk
```

## Compile PDF
```bash
latexmk -e '$pdflatex=q/pdflatex %O -shell-escape %S/' -pdf
```
