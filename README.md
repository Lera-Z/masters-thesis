# Coding of Visual Textures Defined by Local Multipoint Correlations in Rat Visual Cortex

![GitHub](https://img.shields.io/github/license/Lera-Z/master-thesis?color=black) ![GitHub last commit](https://img.shields.io/github/last-commit/Lera-Z/master-thesis)

This repository contains the Bookdown files I used to write my master's thesis [Coding of Visual Textures Defined by Local Multipoint Correlations in Rat Visual Cortex](https://vzelenkova.com/master-thesis/introduction.html).

It is based on the [ai2s-thesisdown template](https://github.com/AI-Student-Society/ai2s-thesisdown), which is in turn based on the [oxforddown template](https://github.com/ulyngs/oxforddown).

### Compilation

The current setup is tested in Ubuntu 18.04 and should be compatible with iOS and Windows with minimal changes.

To setup, run the following

```
install.packages('knitr')
install.packages('bookdown')
tinytex::install_tinytex()
```

To produce the files, open the file `master-thesis.Rproj` using RStudio and run the Build all command (it corresponds to `make pdf`). To produce the Gitbook version, run `make gitbook` in console. All generated files will be found in the generated `docs` folder.