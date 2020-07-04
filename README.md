# ghostwriter-themes

[Ghostwriter](https://github.com/wereturtle/ghostwriter) is a multiplataform distraction-free [Markdown](https://daringfireball.net/projects/markdown) editor. while I consider it a pretty good piece of software, it is still lacking a good variety of themes so users can avoid monotony when they feel like. Here I will collect my experimental themes, and you are invited to contribute yours.

## Theme Documentation

[Wereturtle](https://github.com/wereturtle), the developer of Ghostwriter, has now documented the [Theme spec](https://github.com/wereturtle/ghostwriter/wiki/Theme-File-Format). You should read it there before you venture into theme-making. This is only a rough crash-course for beginners who just want to know where themes are and where they must put new themes.

If you have created some themes and don't want to create a repository of your own, feel free to add them here.

## Where to Look for Inspiration 

* [Atom Theme Gallery](https://atom.io/themes)
* [Best Colour Themes for Text Editors](https://www.slant.co/topics/358/~best-color-themes-for-text-editors)
* [Eclipse Colour Themes](http://www.eclipsecolorthemes.org/)
* Add your own.

## How to import these themes

Ghostwriter does not have any way to import the theme files from the UI of Ghostwriter. 

All custom theme files should reside in `~/.config/ghostwriter/themes` within a directory if its own.

The fastest way to get these themes imported is as follows:

```
mkdir -p ~/.config/ghostwriter/themes
cd ~/.config/ghostwriter/themes
git clone https://github.com/fazlearefin/ghostwriter-themes.git ./
```

After this restart ghostwriter and you should be able to use these custom themes.
