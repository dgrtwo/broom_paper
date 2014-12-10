broom: An R Package for Converting Statistical Analysis Objects Into Tidy Data Frames
=====================

This is a reproducible version of the **broom** manuscript, constructed according to the [R Journal guidelines](http://journal.r-project.org/share/author-guide.pdf). You can reconstruct `Robinson.tex` using knitr:

```
Rscript -e "knitr::knit('Robinson.Rnw')"
```

This requires the following packages:

```
install.packages(c("knitr", "broom", "dplyr", "ggplot2", "Lahman", "survival"))
```

After which the PDF and its references can be compiled into `RJwrapper.pdf` with `pdflatex` and `bibtex`.

The file [sessionInfo.txt](sessionInfo.txt) contains the session used to compile the submitted manuscript.
