
# Latex Packages
```
sudo apt install \
  texlive \ # tex compiler
  latexmk \ # tex autocompile / compile on save
  gv        # pdf viewer that updates when pdf file is rewritten
```

## Compile and view
```
latexmk -outdir=output -pvc -view=none
gv -watch example.pdf
```
