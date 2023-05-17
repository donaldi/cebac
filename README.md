# cebac
Comann Eachdraidh Sgìre a’ Bhac files

Created a LaTeX version of the SCIO constitution to tidy it up and make change-tracking possible.

The main constitution is in the file called constitution.tex.

The EPS file is the logo of the comann and is referenced from the .tex file.

The other (unnumberedtotoc.sty) file is a non-standard and modified LaTeX package. On a clean installation it
must be installed wherever your tex system expects to find sty files. On linux this is generally
```
~/texmf/tex/latex/commonstuff/
```

Assuming the .sty file has been copied to the correct location, running 

```
xelatex constitution.tex
```
OR
```
pdflatex constitution.tex
```

three times should create a pdf file.
