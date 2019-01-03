
# Introduction

## Acknowledgments {-}

All the credit should go to Garrett Grolemund and Hadley Wickham for writing the truly fantastic *R for Data Science* book,
without which these solutions would not exist---literally.

Special thanks to  [\@dongzhuoer](https://github.com/dongzhuoer) for a careful reading of the book
and noticing numerous issues and proposing fixes.

These solutions have benefited from those who fixed problems and contributed 
solutions. Thank you to all of those who contributed on
[GitHub](https://github.com/jrnold/r4ds-exercise-solutions/graphs/contributors) 
(in alphabetical order):
(in alphabetical order) [\@adamblake](https://github.com/adamblake), [\@benherbertson](https://github.com/benherbertson), [\@carajoos](https://github.com/carajoos), [\@dcgreaves](https://github.com/dcgreaves), [\@decoursin](https://github.com/decoursin), [\@dongzhuoer](https://github.com/dongzhuoer), [\@GoldbergData](https://github.com/GoldbergData), [\@gvwilson](https://github.com/gvwilson), [\@JamesCuster](https://github.com/JamesCuster), [\@jmclawson](https://github.com/jmclawson), [\@KleinGeard](https://github.com/KleinGeard), [\@mjones01](https://github.com/mjones01), [\@mvhone](https://github.com/mvhone), [\@nickcorona](https://github.com/nickcorona), [\@nzxwang](https://github.com/nzxwang), [\@RandallEW](https://github.com/RandallEW), and[\@tinhb92](https://github.com/tinhb92).

## Organization {-}

The solutions are organized in the same order, and with the 
same numbers as in *R for Data Science*. Sections without
exercises are given a placeholder.

Like *R for Data Science*, packages used in each chapter are loaded in a code chunk at the start of the chapter in a section titled "Prerequisites".
If a package is used infrequently in solutions it may not 
be loaded, and functions using it will be called using the 
package name followed by two colons, as in `dplyr::mutate()` (see the *R for Data Science* [Introduction](http://r4ds.had.co.nz/introduction.html#running-r-code)).
We will also use `::` to be explicit about the package of a
function.

## Dependencies {-}

You can install all packages used in the solutions with the 
following line of code.

```r
devtools::install_github("jrnold/r4ds-exercise-solutions")
```

## Bugs/Contributing {-}

If you find any typos, errors in the solutions, have an alternative solution,
or think the solution could be improved, I would love your contributions.
Please open an issue at <https://github.com/jrnold/r4ds-exercise-solutions/issues> or a pull request at
<https://github.com/jrnold/r4ds-exercise-solutions/pulls>.

## Colophon {-}



HTML and PDF versions of this book are available at <http://jrnold.github.io/r4ds-exercise-solutions>.
The book is powered by [bookdown](https://bookdown.org) which makes it easy to turn R markdown files into HTML, PDF, and EPUB.

The source of this book is available at <https://github.com/jrnold/r4ds-exercise-solutions>
This book was built from commit [ed171a3](https://github.com/jrnold/r4ds-exercise-solutions/tree/ed171a397f4c887d2d6306ed51df264457c99d82).

This book was built with:

```r
devtools::session_info("R4DSSolutions")
#> ─ Session info ──────────────────────────────────────────────────────────
#>  setting  value                       
#>  version  R version 3.5.1 (2018-12-12)
#>  os       Ubuntu 14.04.5 LTS          
#>  system   x86_64, linux-gnu           
#>  ui       X11                         
#>  language (EN)                        
#>  collate  en_US.UTF-8                 
#>  ctype    en_US.UTF-8                 
#>  tz       UTC                         
#>  date     2019-01-03                  
#> 
#> ─ Packages ──────────────────────────────────────────────────────────────
#>  ! package       * version date lib source
#>  R R4DSSolutions   <NA>    <NA> [?] <NA>  
#> 
#> [1] /home/travis/R/Library
#> [2] /usr/local/lib/R/site-library
#> [3] /home/travis/R-bin/lib/R/library
#> 
#>  R ── Package was removed from disk.
```

<!-- match unopened div --><div>
