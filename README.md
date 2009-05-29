## OOCSS TextMate Bundle

This TextMate bundle provides snippets for use with [OOCSS framework](http://wiki.github.com/stubbornella/oocss).

### Install

I recommend using GetBundles to install the OOCSS bundle, but feel free to install it manually or via the terminal.

#### A. Using [GetBundles](http://svn.textmate.org/trunk/Review/Bundles/GetBundles.tmbundle/)

See Alex Payne's [excellent introduction](http://al3x.net/2008/12/03/how-i-use-textmate.html) to it.

#### B. Using Git:

Fire up the Terminal and run the following commands.

1. `mkdir -p ~/Library/Application\ Support/TextMate/Bundles`
2. `cd ~/Library/Application\ Support/TextMate/Bundles`
3. `git clone git://github.com/asmala/oocss-tmbundle.git "OOCSS.tmbundle"`
4. `osascript -e 'tell app "TextMate" to reload bundles'`

#### C. Manually

1. Download a [zip file](http://github.com/asmala/oocss-tmbundle/tarball/master) of the latest version.
2. Unzip it if necessary and rename the resulting folder `OOCSS.tmbundle`
3. Open your home folder, then Library > Application Support > TextMate
4. Create a directory called Bundles, if it doesn't exist already
5. Move the OOCSS.tmbundle folder from step 2 to the Bundles folder
6. In TextMate, select Bundles > Bundle Editor > Reload Bundles

### Grids

Currently the bundle comes with tab triggers for lines (`line`) and grid units (`unit`, `1of1`, `1of2`, etc.).

### Modules

It also handles modules, and the associated header, body, and footer, with `mod`, `hd`, `bd`, and `ft`.