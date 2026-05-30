# weedtopics
a LaTeX style sheet to provide icons for when chapters/sections/etc are "in the weeds" aka on a tangent

# installation

Copy this file to the directory of your .tex document and then put this in the preamble:

```
\usepackage{weedtopics}
```
then to make a section, chapter, subsection or paragraph:

```
\weedsection[1]{Title}  % level 1: slightly tangential
\weedsection[2]{Title}  % level 2: very tangential
\weedsection[3]{Title}  % level 3: esoteric
\weedchapter ...    % chapter
\weedsubsection ... % subsection
\weedspecial[<level>]{<topic>}   % paragraph
```

# demo

You only really need the .sty file, but the main.tex file gives an example of the usage of this .sty file

# LyX

To include this .sty file in Lyx, you can use the weedtopics.module.

To install it, put it in the Lyx layouts folder

- Windows: C:\Users\<username>\AppData\Roaming\LyX<version>\layouts\
- Mac: ~/Library/Application Support/LyX<version>/layouts/
- Linux: ~/.lyx/layouts/

Then reconfigure LyX: In the LyX top menu, go to Tools ➔ Reconfigure.

Then restart LyX.

Then activate the module
- Open Settings: Go to Document ➔ Settings from the top menu bar.
- Navigate to Modules: Click on the Modules tab on the left-hand panel.
- Select and Add: Find your module in the Available list, click on it,
  and click the Add button to shift it to the "Selected" list.
- Save Changes: Click OK to apply the module to the current
  document. You can also click Save as Document Defaults if you want
  it enabled for all future files
