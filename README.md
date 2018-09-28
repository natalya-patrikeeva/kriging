## Prerequisites

Install R (I recommend the new version 3.5.1) from [here](https://cloud.r-project.org/):

After R is installed, launch R from terminal by typing `R`:

```R
R version 3.5.1 (2018-07-02) -- "Feather Spray"
Copyright (C) 2018 The R Foundation for Statistical Computing
Platform: x86_64-apple-darwin15.6.0 (64-bit)
...

> install.packages('devtools')
> devtools::install_github('IRkernel/IRkernel')
> IRkernel::installspec()
> q()
```

Start Jupyter notebook and select R kernel from New dropdown menu.

```
jupyter notebook
```

