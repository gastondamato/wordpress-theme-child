# Wordpress Theme Child
## A wordpress theme child so you don't modify the actual theme
 
### how to use it

First edit style.css to extend the theme that you would like to use.
In this example I'm using Divi, so I'm importing the divi's style.css like so:

```css
@import url("../Divi/style.css");
```

Change **Divi** with the folder of the theme you want to use located inside wp-content/themes.

The rest is self-explanatory. You can replace the commented section. Wordpress will read this data to show it inside the theme area.

Do not forget to change of the template property with the name of your parent theme’s folder (as named inside your wp-content/themes folder)


After that you can replace **screenshot.jpg** with the image you want wordpress to show on the themes section.

Then, respecting the structure of the theme you are extending, you can create a php file to add the functionality you need.

I added 3 files just to show how to extend it:[^1]
```
/function.php
/footer.php
/includes/social_icons.php
```
[^1] Remember that the .php files have to be at the same location of the parent theme.

Copy this folder inside wp-content/themes

