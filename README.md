
Gonna do that tonight
-Luciano



### Organisation of the LaTex project
Files
- `main.tex` 
    Contains the definitions of the LaTeX project, \usepackage{}, 
    Contains also some control flow to display/hide specific sections of the document when compiling the pdf (around lines 120-135). To hide/display said sections, change the number between bracket to 0/1. To display everything, turn \finished to 1.
- `body.tex`
    Contains \import statements to the section subfiles. 
    This also allow to comment in/out entire section easily.
- `Appendix.tex`
    Contains \import statements to the appendices subfiles. 
- `abstract.tex`
        .tex file containing the abstract.
- `00_titlepage.tex`
        .tex file containing the titlepage.
- `README`
    This document.

Folders
- `body/`
This folder contains the tex files with the actual text. 
  - `body/01-Introduction.tex`
        .tex file containing Section 1 (Introduction).
- `Appendices/`
    This folder contains the appendices. 
- `Image/`
    This folder contains the image files used in our projects.


