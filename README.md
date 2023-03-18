# Latexfinder-2-character-sheet
A Latex package to compile Pathfinder 2 character sheets.

## Use
It is possible to utilize the Latexfinder 2 character sheet either as a local package or as the whole project.

### As a package
- Clone or download [Latexfinder-2-character-sheet](https://github.com/Jocarnail/Latexfinder-2-character-sheet) from GitHub
- Place into the project's folder
- Import the package using it's relative path. For example:
```latex
\usepackage{./Latexfinder-2-character-sheet/pf2charactersheet}
```
- If you want to use also the provided document styling, also add the ```pf2characterStyle``` package by its relative path.
```latex
\usepackage{./Latexfinder-2-character-sheet/pf2characterstyle}
```
> #### **Warnings**
> 
> When loaded as a local package, the compilation of the project will throw the following, or similar, warnings:
> ```latex
> You have requested package `./Latexfinder-2-character-sheet/pf2charactersheet`, but the package provides `pf2charactersheet`.
> ```
>
> This is expected


## Page fit
Because the size of the original character sheet is *letterpaper*, the image will fit full page while using letterpaper size pages. 

The project fits A4 paper fine, however, space is left at the bottom of the page, since the proportions of the page are different.

Moreover, a the moment the position of the numbers on the sheet is not identical for different page sizes.