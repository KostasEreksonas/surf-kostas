# surf-kostas

# Table of contents
===================
* [surf-kostas](#surf-kostas)
* [My custom Surf browser build](#My-custom-Surf-browser-build)
* [Patches that I have applied](#Patches-that-I-have-applied)
* [Installation guide](#Installation-guide)

# My custom Surf browser build
My custom build of suckless surf browser. This is a part of me trying some suckless software.

# Patches that I have applied

In this section I will list patches that I have applied to my custom ***Surf*** browser build:

* [Bookmarks](../main/patches/surf-bookmarks-20170722-723ff26.diff) - a patch for adding bookmarks with ***Ctrl + m*** keybind.
* [Homepage](../main/patches/surf-2.0-homepage.diff) - a patch for setting a homepage within Surf web browser.

# Installation guide

In this section I will provide instructions for installing my custom `surf` browser build.

1. Clone this git repository:

`git clone https://github.com/KostasEreksonas/surf-kostas.git`

2. Go to the folder of the cloned repository:

`cd surf-kostas`

3. Build the package:

`make`

4. Compile this custom `surf` build ***with root privilleges***:

`sudo make clean install`

5. Done!
