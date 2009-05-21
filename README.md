## OOCSS TextMate Bundle

This TextMate bundle provides snippets for use with [OOCSS framework](http://wiki.github.com/stubbornella/oocss).

### Install

**A. Recommended:** Use [GetBundles](http://svn.textmate.org/trunk/Review/Bundles/GetBundles.tmbundle/).

B. With Git:

1. `mkdir -p ~/Library/Application\ Support/TextMate/Bundles`
2. `cd ~/Library/Application\ Support/TextMate/Bundles`
3. `git clone git://github.com/asmala/oocss-tmbundle.git "OOCSS.tmbundle"`
4. `osascript -e 'tell app "TextMate" to reload bundles'`

C. Without Git:

1. `mkdir -p ~/Library/Application\ Support/TextMate/Bundles`
2. `cd ~/Library/Application\ Support/TextMate/Bundles`
3. `wget http://github.com/asmala/oocss-tmbundle/tarball/master`
4. `tar zxf oocss-tmbundle*.tar.gz`
5. `rm oocss-tmbundle*.tar.gz`
6. `mv oocss-tmbundle* "OOCSS.tmbundle"`
7. `osascript -e 'tell app "TextMate" to reload bundles'`

### Grids

Currently the bundle comes with tab triggers for lines (`line`) and grid units (`unit`, `1of1`, `1of2`, etc.).

### Modules

It also handles modules, and the associated header, body, and footer, with `mod`, `hd`, `bd`, and `ft`.