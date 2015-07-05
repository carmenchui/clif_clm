# BBEdit Common Logic Interchange Format Codeless Language Module

This repository contains instructions on how to enable CLIF syntax
coloring in BBEdit 8.5.5, TextWrangler 4.5.12 and later with standard and your custom tags and types. It can also be used to include and Lasso how to use AppleScript to switch language modes between CLIF, HTML and JavaScript.

Installation Instructions
=========================

1. Clone the GitHub repository `BBEdit_CLIF_CLM
   <https://github.com/carmenchui/BBEdit_CLIF_CLM>`_ or download the
   ``.zip`` file
2. Backup and remove all other LDML Language Modules from
   ``~/Library/Application Support/BBEdit/Language Modules``. This avoids
   possible conflicts.
3. Move the file ``BBEditLDML/Language Modules/LassoScript.plist`` to
   ``~/Library/Application Support/BBEdit/Language Modules``.
4. Move the folder ``BBEditLDML/Scripts/06)Set Language to/`` and its contents
   to ``~/Library/Application Support/BBEdit/Scripts/``.
5. Restart BBEdit. This will load the new ``.plist`` and AppleScripts.  Next
   you configure BBEdit to use these items.
6. In BBEdit, select `BBEdit > Preferences > Languages > Suffix Mappings`. Map the file suffixes that you want to have CLIF syntax highlighting to the appropriate language module.  You might need to `Add...` or `Change...` file suffixes. I recommend mapping ``.clif``. For each suffix, set the name of the suffix, set the language to `CLIF`, and select the radio button for `Source File`.
8. Under the `Scripts` menu (the funny scroll icon shaped like an ``S``),
   select `Set Language to > CLIF`.
9. You can set keyboard shortcuts for these scripts to easily switch language
   modes.  Select `Window > Palettes > Scripts`. Expand `Set Language to`.
   Select `HTML`. Click `Set Key...`. I use ``^H`` (CTRL-H) for HTML, and
   ``^C`` for CLIF.
10. Create a new file, name it ``test.clif``, set the language to `CLIF`, and syntax coloring should work.

# Download

[You can download the plist file here.](https://github.com/carmenchui/BBEdit_CLIF_CLM/releases/)

# Screenshots
![test](https://github.com/carmenchui/BBEdit_CLIF_CLM/raw/master/clif_example1.jpg)

![test](https://github.com/carmenchui/BBEdit_CLIF_CLM/raw/master/clif_example2.jpg)


# License
Copyright (c) 2015 Carmen Chui, University of Toronto

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 