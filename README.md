# NotexBook

To speed up self-studying and organizing texts in that would otherwise rest in a paper notebook.

This actually a LaTeX package optimized for my notetaking style.

## Prerequisites

As we do not support paper to LaTeX conversion notepads, one must write their notes with LaTeX.

## Installation

### Direct Usage

1. Copy the files from ```src``` to your project root directory.
2. Place ```\documentclass{notexbook-full}``` in the beginning of your ```<file_name>.tex``` file.
3. If that did not work, check the relative path in the file name.

### TexLive (Ubuntu)

I could not execute .sh -file. But opening the project directory and running the commands in ```quick-install.sh``` would work.

1. Copy the files from ```src/``` to ```~/texmf/tex/latex/notexbook```.
2. Run ```texhash ~/texmf```.
3. Try to compile the documentation.

### TexLive (Windows 10)

Warning: I am not sure about the fourth step!

1. Open file ```C:\texlive\2018\texmf.cnf```. The installation path may differ.
2. Add ```TEXMFLOCAL = C:\texlive\texmf-local``` to the file.
3. Copy the files from ```src``` to ```C:/texlive/texmf-local/tex/latex/base```. I am not sure about the location!!!!
4. Run ```texhash``` in command prompt.
5. Try to compile the documentation.

## License

The "docs" and "examples" folders are licensed under [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The rest are under [MIT License](https://choosealicense.com/licenses/mit/).