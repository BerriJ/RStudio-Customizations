# RStudio-Customizations

This is a fork of riley-roachs beautiful project which customizes the R-Studio appearance.

The only difference to  riley-roachs project is the theme file for the Solarized Dark theme. Look at the Screenshot below to see how it looks. 

Please create an issue if you have any problems!

### Darker RStudio with Editor Theme

> Darker Modern Theme with Solarized Dark
![DarkRStudio](images/dark-rstudio.png)

<hr>

# Using "Dark" RStudio
I've made some edits to RStudio's "Modern" theme to resemble VS Code's Dark+ theme. To use this theme, you'll need to do a few things. First, go to "~/Applications/RStudio.app/Contents/Resources/www/" (Windows) and "~/usr/lib/rstudio/www/" on Linux and paste custom_styles.css in that directory. Next, paste "index.htm" into the same directory, and allow this file to replace the old "index.htm"

# Using Custom Editor Themes

The themes I've changed are Cobalt and Solarized Dark. If you do not want to change these files specifically, you can select another one of the files located in "~/rstudio/" and paste one of these files in there. Once you've made the changes, you'll need to Quit RStudio and then Open the app once more. The changes should have been made!

## Make Your Own Custom Editor Theme
To make your own custom theme, you'll need to locate the folder that contains the .css files for themes. If your RStudio app is located in the applications folder, then the path should be
"~/Applications/RStudio.app/Contents/Resources/www/rstudio/".

Another handy tool when customizing your own theme is the "Inspect" command. Here, you can make real-time changes to RStudio and see how your theme would look.

<hr>

