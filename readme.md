# Hugo Starter Theme

Dead-simple Hugo theme with everything you need to get started. Intended to be a starter for creating your own theme without including useless bloat like most Hugo themes.

Forked from https://github.com/ericmurphyxyz/hugo-starter-theme, with modifications from https://github.com/yihui/hugo-lithium to make it work better with [**blogdown**](https://github.com/rstudio/blogdown) 

## Getting started

The easiest way to get started is to create a new (empty) RStudio project, then 



```r
devtools::install_github('rstudio/blogdown')  # install blogdown
blogdown::install_hugo()  # install Hugo
blogdown::new_site(theme = 'KimeyQuimey/hugo-starter-theme-r')
```

Then you should be able to see an example website launched in the RStudio Viewer.

To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).
