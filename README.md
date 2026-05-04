# From Chemistry to Life: Scientific Theories on the Origin of Life

This is a Bookdown project for an academic overview of major scientific theories on the origin of life.

## Build

In RStudio or the R console, run:

```r
bookdown::render_book("index.Rmd")
```

## Important folder structure

All `.Rmd` chapter files are kept in the project root because `_bookdown.yml` uses:

```yaml
new_session: true
```

Figures are stored in the `figures/` folder and referenced using relative paths such as:

```r
knitr::include_graphics("figures/01_theory_map.png")
```
