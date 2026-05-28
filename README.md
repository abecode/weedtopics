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
