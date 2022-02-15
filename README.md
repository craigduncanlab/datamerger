# Datamerger

(c) 2019-2022 Craig Duncan www.craigduncan.com.au

# Document data merge workflow

Use R Markdown and knitr to create a merged text file that you can use as the input text file for 'autostyler'

See example file : KnitExample.Rmd

Then run the following from an R Studio console:

```
rmarkdown::render(input = "~/Documents/Path/KnitExample.Rmd",intermediates_dir="~/Documents/Path/output",run_pandoc=FALSE)
```

This will produce a markdown output file with .md extension, in the output folder.

Use this as the input file for the workflow above.