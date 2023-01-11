# Resources
A collection of stuff I use all the time and find super useful.

## Visualization

(plotting with ggplot2, but also general resources that are independnet of software)

### General datavis principles
Lisa Charlotte Muth at Datawrapper writes short and really clear articles rich with examples on datavis dos and don’ts, that are general across any graphical tool or programming language. [Here is the whole list](https://blog.datawrapper.de/category/datavis-dos-and-donts/), but many of them are specifically linked below under the appropriate topics.

Datawrapper | [What to think about when creating charts](https://blog.datawrapper.de/better-charts/)

### Fonts
Datawrapper | [Which fonts to use for your charts and tables](https://blog.datawrapper.de/fonts-for-data-visualization/). Amazing introduction, talks about all the parameters that go into a font.

Pimp my type | https://pimpmytype.com/free-quality-fonts/

[`showtext`](https://cran.rstudio.com/web/packages/showtext/vignettes/introduction.html) | Favorite package for fonts in ggplot2 (and rmarkdown-based stuff), you can use any font from [Google Fonts](https://fonts.google.com/)

[Setting up and debugging custom fonts](https://yjunechoe.github.io/posts/2021-06-24-setting-up-and-debugging-custom-fonts/) | `ragg`, `systemfonts`, etc., a possible alternative to `showtext`. 

### Colors
Datawrapper | [What to consider when choosing colors for data visualization](https://blog.datawrapper.de/colors/)

Specific color related topics from Datawrapper: 
- [Diverging vs. sequential color scales](https://blog.datawrapper.de/diverging-vs-sequential-color-scales/)
- [Colorblindness](https://blog.datawrapper.de/colorblindness-part2/)
- [Classed vs. unclassed color scales](https://blog.datawrapper.de/classed-vs-unclassed-color-scales/)
- [Quantitative vs. qualitative color scales](https://blog.datawrapper.de/quantitative-vs-qualitative-color-scales/)
- [Which color scale to use in datavis](https://blog.datawrapper.de/which-color-scale-to-use-in-data-vis/)
- [10 ways to use fewer colors in your data visualization](https://blog.datawrapper.de/10-ways-to-use-fewer-colors-in-your-data-visualizations/)
- [Colors for gender data](https://blog.datawrapper.de/gendercolor/)

Color palettes:
- [colorspace: ggplot2 color scales](https://colorspace.r-forge.r-project.org/articles/ggplot2_color_scales.html): A very organized R package that lets you set up custom color palettes but also has some built in. Very helpful for continuous color palettes. Contains the `darken()`/`lighten()` functions.
- [Canva color palettes](https://www.canva.com/learn/100-color-combinations/):  These consist of 4 colors each.
- [Paul Tol's palettes](https://cran.r-project.org/web/packages/khroma/vignettes/tol.html): Good for color blindness, screeen/paper, etc.

### Types of graphs
- [The R Graph Gallery](https://r-graph-gallery.com/)

### Tables

Datawrapper | [What to consider when creating tables](https://blog.datawrapper.de/guide-what-to-consider-when-creating-tables/)

[`gtExtras`](https://themockup.blog/posts/2022-06-13-gtextras-cran/) | Package that expands on the `gt`package for creating tables

[Advanced R topics: gt tables](https://aosmith16.github.io/spring-r-topics/slides/week04_gt_tables.html#1 ) Super nice presentation on `gt` by Ariel Muldoon. The slides are made in Xaringan and also shows off that really well! Part two of the presentation is [here](https://aosmith16.github.io/spring-r-topics/slides/week05_gt_flair.html#1) (colors, themes, etc.)

[kableExtra](http://haozhu233.github.io/kableExtra/awesome_table_in_pdf.pdf)| Tables for pdfs, useful for academic articles.

### Useful packages for `ggplot2` 

[`patchwork`](https://patchwork.data-imaginist.com/) | Combining multiple ggplot objects

[`ggpubr`]( https://rpkgs.datanovia.com/ggpubr) | Publication ready plots in `ggplot2`. In particular, I often use this package for adding **brackets** (`geom_bracket()`) or `theme_transparent()` for adding a transparent background (useful for presentations).

[`showtext`](https://cran.rstudio.com/web/packages/showtext/vignettes/introduction.html) | Changing fonts in `ggplot2` plots (or anything based on Rmarkdown)

[How to Create Engaging and Complex Visualizations in R](https://rstudio-conf-2022.github.io/ggplot2-graphic-design/)| Really great `ggplot2` workshop by Cédric Scherer, covers many technical aspects of `ggplot2`.


## Cheatsheets

- [`ggplot2` cheatsheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-visualization.pdf)
- [`dplyr` cheatsheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-transformation.pdf)
- [Themes in `ggplot2` cheatsheet (Emma's version)](https://emmaskarstein.github.io/images/cheatsheets_themes.pdf)
- [Themes in `ggplot2` cheatsheet (Clara Granell's version)](https://github.com/claragranell/ggplot2/blob/main/ggplot_theme_system_cheatsheet.pdf)
- [Package development cheatsheet](https://raw.githubusercontent.com/rstudio/cheatsheets/master/package-development.pdf)

## Presentations

### Xaringan
My favorite way to make presentations is the Rmarkdown extension https://bookdown.org/yihui/rmarkdown/xaringan.html.

Some xaringan resources:
- Extra functionality: https://github.com/gadenbuie/xaringanExtra 
- Themes: https://pkg.garrickadenbuie.com/xaringanthemer/articles/xaringanthemer.html 
- How to include references and citations: https://github.com/yihui/xaringan/wiki/Bibliography-and-citations (you will need to look at the documentation for RefManageR as well, most helpful is the help page `?RefManageR::BibOptions`. (This may be helpful too: https://github.com/yihui/xaringan/issues/26#issuecomment-368320444) 

## R package development

- [Package development cheatsheet](https://raw.githubusercontent.com/rstudio/cheatsheets/master/package-development.pdf)
- [Using `ggplot2` in R packages](https://ggplot2.tidyverse.org/articles/ggplot2-in-packages.html)
  - [Paleolimbot: `electionca`](https://github.com/paleolimbot/electionca) | A really nice example package that shows how to use `ggplot2` in a package.

## Making websites

[Publishing a Quarto website with GitHub Pages](https://quarto.org/docs/publishing/github-pages.html#render-to-docs)

## Regex

- [regex101.com](https://regex101.com/) | Testing regular expressions

## Other people's blogs
- [Cara Thompson: *Building stories with data*](https://www.cararthompson.com/blog.html) (lots of useful stuff in the "Talks" tab as well!)
