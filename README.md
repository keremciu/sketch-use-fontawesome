sketch-use-fontawesome
=================

Its a nice plugin to use fontawesome in Sketch for developers and designers.

# New feature: Select an icon from Archive
![demo][newdemo-image]
> Note: yep, I know it doesn't look good but I found this solution(NsComboBox) to choose an icon.


=================
![demo][demo-image]

# Features

> `A Problem of the Designer:` 
> When you want to add an icon from fontawesome, you don't need to find a cheatsheet to copy it in your design.

- You can easily add it with alias of the icon.

> `A Problem of the Developer:` 
> When you want to learn the alias of the icon which is added from a designer, you don't need to look all of 585+ icons to find it.

- You can easily learn it with one click.

# Install

1. Download ZIP of this repo.
2. Extract and rename folder to what would you like.
3. Put the folder in your Sketch plugin folder (Use `Plugins > Reveal Plugins Folder` to find the plugin folder).

# Dependencies

1. You need to install fontawesome font to your os system. You can download from here: https://github.com/FortAwesome/Font-Awesome/raw/master/fonts/FontAwesome.otf

# Usage

#### for designer

1. Insert a text layer in sketch document.
2. Select `Add Icon with Alias` under the plugin in `Plugins` menu.
3. Write the alias of icon which you want to add.

#### for developer

1. Select the text layer of icon.
2. Select `Get Alias of Icon` under the plugin in `Plugins` menu.

# Note

It will be helped you only when you use font awesome font. 

~~I'll be add some functions, one of them: you can add icon from font awesome icon list.~~

Do you have any suggestion? it would be so nice.

# Next steps

- I'm trying to build a Clean UI for archive view. We'll select icons from the tableview(nstableview).
- I'm trying to create a new plugin, it will include material-icon-font and svg icon font parser. 
- I will add "icon categories" in "Add icon from Archive". I'll be using it to filter icons.
- I need to delete unnecessary codes.
- I need to add more annotations and good instructions.

# License

MIT

[demo-image]: http://i.imgur.com/7Hbgdc2.gif
[newdemo-image]: http://i.imgur.com/14cAdjI.gif
