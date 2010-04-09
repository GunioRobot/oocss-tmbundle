# OOCSS TextMate Bundle #

This TextMate bundle provides snippets for use with [OOCSS framework](http://wiki.github.com/stubbornella/oocss).

## Install ##

I recommend using GetBundles to install the OOCSS bundle, but feel free to install it manually or via the terminal.

### A. Using [GetBundles](http://svn.textmate.org/trunk/Review/Bundles/GetBundles.tmbundle/) ###

See Alex Payne's [excellent introduction](http://al3x.net/2008/12/03/how-i-use-textmate.html) to it.

### B. Using Git: ###

Fire up the Terminal and run the following commands.

1. `mkdir -p ~/Library/Application\ Support/TextMate/Bundles`
2. `cd ~/Library/Application\ Support/TextMate/Bundles`
3. `git clone git://github.com/asmala/oocss-tmbundle.git "OOCSS.tmbundle"`
4. `osascript -e 'tell app "TextMate" to reload bundles'`

### C. Manually ###

1. Download a [zip file](http://github.com/asmala/oocss-tmbundle/tarball/master) of the latest version.
2. Unzip it if necessary and rename the resulting folder `OOCSS.tmbundle`
3. Open your home folder, then Library > Application Support > TextMate
4. Create a directory called Bundles, if it doesn't exist already
5. Move the OOCSS.tmbundle folder from step 2 to the Bundles folder
6. In TextMate, select Bundles > Bundle Editor > Reload Bundles

## Usage ##

Currently the bundle supports most elements used in OOCSS. These include grids, modules, tabs, and breadcrumbs, as well as the OOCSS template.

### Grids ###

Currently the bundle comes with tab triggers for lines (`line`) and grid units (`unit`, `1of1`, `1of2`, etc.).

### Modules ###

It also handles modules, and the associated header, body, and footer, with `mod`, `hd`, `bd`, and `ft`. Talk bubbles can be created with `bubble`.

### Tabs ###

A full tab module can be created with `tbs` and the associated tabs with `tb`. To create an area for tab controls, such as a close button, use `tbcs` and add the controls with `tbc`. Tab body sections can be created with `tbb`.

### Breadcrumbs ###

The tab trigger for the breadcrumbs element is `bcs`, while an individual breadcrumb can be created with `bc`.