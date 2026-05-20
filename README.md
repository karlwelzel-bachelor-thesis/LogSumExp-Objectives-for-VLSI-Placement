# LogSumExp Objectives for VLSI Placement
My bachelor thesis for the BSc in Mathematics at the University of Bonn.

## Original
You can find the original PDF [here](20200722_Bachelor%20Thesis.pdf). Some PDF features are only usable after downloading the document. Note that there is an error in the statement and proof of Theorem 4.7. The details of the mistake and a proof for a weaker claim are given [here](20210122_Correction_Properties%20of%20WA.pdf).

## Compiling
On Linux after the usual LaTeX setup (I used the TeX Live packages) clone this repository and run
```
mkdir build
pdflatex -synctex=1 -interaction=nonstopmode -output-directory=build main.tex
biber build/main.bcf
pdflatex -synctex=1 -interaction=nonstopmode -output-directory=build main.tex
```
The output can be found in `build/main.pdf`.

## Contributions
I'd like to thank [m8mble](https://github.com/m8mble), Pascal van Cleeff and Jannik Silvanus for allowing me to use their bachelor thesis template. All of the files in the `settings` directory are adapted from their work.

The title page was adapted from the template provided by the University of Bonn (https://www.mathematics.uni-bonn.de/files/bachelor/ba_titelseite.zip). 
The `BA_Titelseite.sty` file is explicitly excluded from the license found in `LICENSE`.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
