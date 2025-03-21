# Dynamic reporting with R and Quarto: reanalyzing the Titanic dataset

## What you need on your computer

-   R <https://stat.ethz.ch/CRAN/>
-   RStudio Desktop <https://posit.co/download/rstudio-desktop/>
-   git <https://git-scm.com/downloads>

## Get started

1.  Download the repository locally

```         
git clone https://github.com/schw4b/titanic.git
```

2.  Open the titanic project and the analysis file

-   Start RStudio, click the Menu "File", "Open Project...", and open the file `titanic.Rproj`.
-   Click "File", "Open File.." and open the Quarto Document `titanic.qmd`.

3.  Install the required R packages

``` r
install.packages("carData")
install.packages("testit")
```

4.  Press "Render"

You should see the final document in your browser, just like here on my website <https://www.statsyup.org/titanic/>.

## How to publish this document?

```
quarto publish gh-pages titanic.qmd
```