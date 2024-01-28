# Computer Assisted Proof - Project Report
## AKS primality test

Project done as partial requirement of the Project Assisted Proof course at VU Amsterdam, Spring 2024.

### Group members
- Luciano Baldassi
- Justus de Bruijn Kops
- Mark Lapidus
- Daniela MacKay
- Martin Rodriguez
- Tristan Vermeulen

### Division of labour
**Understanding of the proof**
- Mark
- Martin
**Lean**
- Luciano
- Justus
- Daniela
**Implementation of the algorithm in Sage**
- Tristan






### Organization of the LaTeX project
**Files**
- `main.tex`  
    Contains the definitions of the LaTeX project, \usepackage{}, \begin{document}, and general layout.
    This file also contains some control flow to display/hide specific sections of the document when compiling the pdf (around lines 120-135). To hide/display said sections, change the number between bracket to 0/1. To display everything, turn \finished to 1.
- `custom_commands.sty`
    Contains some custom commands, math operators, etc, that are specifically useful for this project.
- `body.tex`  
    Contains \import statements to the section files and subfolders. 
    This also allow commenting in/out entire section easily.
- `appendix.tex`  
    Contains \import statements to the appendices files and subfolders. 
    This also allow commenting in/out entire section easily.
- `abstract.tex`  
    .tex file containing the abstract.
- `00_titlepage.tex`  
    .tex file containing the code of the title page.
- `lstlean.tex`
    Define the Lean formatting of listing environments
- `README.md`  
    You are reading it.
- `bibliography.bib`  
  BibTeX file containing the references for the Bibliography

**Folders**
- `body/`  
This folder contains the subfolder and files of the body of the report. Prefix section files and subfolders with a number to keep the folder organized. 
  - `body/01-Introduction.tex`  
    .tex file containing Section 1 (Introduction).
  - ...
- `Appendices/`  
    This folder contains the appendices. 
- `Image/`  
    This folder contains the image files used in our projects.
- `Code/`
    This folder contains the code to be inserted into listings


