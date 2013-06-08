# Solarized Theme

A Solarized theme (and color scheme) for Sublime Text 2.

## Installation

To install in Sublime Text 2, ```$ cd``` into your Packages directory. If you're on a Mac, this is probably something like:

```bsh
$ cd ~/Library/Application Support/Sublime Text 2/Packages
```

Then clone the repo:

```bsh
$ git clone git@github.com:paulcpederson/solarized-sublime.git Theme\ -\ Solarized/
```

The ```Theme\ -\ Solarized/``` bit just names the folder "Theme - Solarized" to keep it inline with Sublime Text's theme naming conventions.

Then add two lines to your user preferences file (Preferences > Settings - User):

```
"color_scheme": "Packages/Theme - Solarized/Solarized (dark).tmTheme",
"theme": "Solarized Dark.sublime-theme"
```

When you save the file, it should automatically change the theme.
