# gtksourceview_cython_lang

## About

A cython language syntaxic analyzer for gtk source code editor (gedit, gnome-builder).

## Features

* inherit python 3 language definitions
* extended with cython keywords
* special handling of c-style function declaration
* special handling of cython compile time statement
* add u prefix to string declaration

## Installing

Put the file 'cython.lang' in your '~/.local/share/gtksourceview-4/language-specs/' folder. After this you could restart your prefered source code editor. For gnome-builder you should go to preferences->languages and find Cython in the list, here you can switch on all the general features and set other preferences for cython like you want. Enjoy!

## License

cython.lang is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.
