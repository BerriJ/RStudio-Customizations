# daRkStudio

This is a fork of riley-roachs beautiful project which customizes the R-Studio appearance.

Please create an issue if you have any problems.

Using this configuration for RStudio is easy, and only requires overwriting two (for now) files, `index.htm` and `custom_styles.css`, into RStudio's application directory. `index.htm` is rarely updated, so you'll likely only need to do this once. Nearly all of the updates from me pertain to `custom_styles.css`. This project is a work in progress, and is something I did because the blue color of RStudio's Modern theme left a bad taste in my mouth. I have little experience in writing css and javascript, and even less experience in building IDEs. If anyone would like to help out by contributing, please do! I'd love the help :).

Please create an issue if you have any problems!

### Darker RStudio

> Darker Modern Theme
> ![DarkRStudio](images/dark-rstudio.png)

<hr>

## Using "Dark" RStudio

To use this theme, you'll need to do the following things:

# MacOS

First, go to `~/RStudio.app/Contents/Resources/www/` and paste `custom_styles.css`  and `index.htm` in that directory and allow the replacement of the old `index.htm`.

# Linux

First, go to `~/usr/lib/rstudio/www/` on Linux and paste `custom_styles.css`  and `index.htm` in that directory and allow the replacement of the old `index.htm`.

# Windows

This should also work on windows. I'm not a windows person so please let me know if you figures out where to place the 2 files on windows.
