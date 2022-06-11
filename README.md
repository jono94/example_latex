
## Latex Packages
```
sudo apt install \
  texlive \ # tex compiler
  latexmk \ # tex autocompile / compile on save
  gv        # pdf viewer that updates when pdf file is rewritten
```

## Compile and view
`latexmk` is supposed to be able to update the pdf view when it recompiles, however this didn't seem to work, hence the use of `gv`.
```
latexmk -outdir=output -pvc -view=none
gv -watch example.pdf
```

## Useful links
* [Class Types](https://latex-tutorial.com/documentclass-latex/)
