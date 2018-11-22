# Thesis-Report

Latex code required to produce my Master Thesis

How to compile

```
xelatex -synctex=1 -interaction=nonstopmode -shell-escape thesis.tex 
bibtex thesis.aux
xelatex -synctex=1 -interaction=nonstopmode -shell-escape thesis.tex 
```