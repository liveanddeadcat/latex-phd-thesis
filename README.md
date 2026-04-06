# Introduction
I made this LaTeX template for my phd thesis (Faculty of Medicine and Health, University of Sydney). Cause word crashed my honours thesis and the hussle formatting a large document was enough. This is a very simple template that let you focus on writing several chapters separately then combine them smoothly! Don't worry if you are new to this system. I've already configured the overall template and the folder structure. You can basically download this folder and start using it. I also included some common math and special case annotations. I work in virus immunology and statstical modelling, so my examples may be a bit biased to these. But there are also plenty of cheatsheets online.

(Author: Yuchen Li. Language used: TeX. Software versions: MikTeX v25.12, TeXStudio v4.9.3, JabRef v6.0)

# Why LaTeX for thesis writing?
- Free, open source workflow, no lisencing issue.
- You just focus on writing. No extra clicking to format things or moving text and figures around. Let LaTeX handles them!
- Easy math and science notations
- Handles large documents and cross-reference better
- Easy troubleshooting, clear error messages, large community and open resources online.

# Get started
Folder structure:
- main.tex - this is the masterdocument consisting of the overall structure of your thesis.
- title.tex - a customized title page according to the theses in our group. Feel free to modify it. 
- references.bib - the reference file. Need to check it and clean things up yourself if you export it from Endnote.
- chapters\ folder - where you store your sub .tex files for each chapter. 
- images\ folder - store your images here.

### Prep
- Make sure you have 3 things installed: a LaTEX distribution that works with your OS (I'm using MikTeX on Windows), a TEX editor (I'm using TeXStudio), bib-supporting reference managers (I'm using JabRef).
- Clone or download this repository and save at the path you like.
- If you are new to LaTeX, I highly recommend you to familiarise yourself with the basics before using this template. It's used to quickly format documents using markup language. You just write text and commands, and LaTeX handles all the formatting! No moving around text and figures every time!
- You may also want to consider installing a universal file converter [pandoc](https://pandoc.org/MANUAL.html). This enables easy .tex to .txt or .tex to .docx converting so you can count words or present to your supervisors easily.
  
### The main files you will be working with
- main.tex
- chapters\Ch1.tex, Ch2.tex....
- images\<your-images-stored-as .png or .jpg>
- references.bib
- (other auxiliary, log, .lot, .pdf, .toc files are automatically generated when you compile. Delete them when you want a clean re-start when compiling. But you don't have to modify them much.)

### Exporting references from a reference manager software
I will use EndNote as an example as our Uni supports this app and it's widely used in our group. But I'm sure there will be plenty of tutorials out there if you are using other ones.

1. Select the references that you want in EndNote.
2. Go to Export > Export as a plain text file, style = "BibTeX".
3. Go to your exported txt file, do some cleaning as you want, then copy the entry into the references.bib.
4. Cite in your .tex files as you go. 

Otherwise, [JabRef](https://github.com/JabRef/jabref) is a pretty good one to format your .bib format references, and cite-as-you-write in TeXStudio.

# References
https://www.youtube.com/@ShareLaTeX   

https://www.sydney.edu.au/research/graduate-research/current-students/thesis-and-examination/preparing-your-thesis.html

# Questions and contact
[Email me](mailto:yuchen.li@sydney.edu.au) if you got any questions.
Please consider mentioning me and this repository if you use this template :).
