# PoliTO - Master Thesis

Source code of my Master Thesis and presentation slides written in LaTeX, for the M.Sc. in *Data Science and Engineering* at Politecnico di Torino. The subject of my Master Thesis is "Approaches for Domain Adaptive Object Detection in Production Environments".

## Master Thesis

The [Master Thesis](./thesis) is written in LaTeX using the [TOPtesi](https://www.ctan.org/pkg/toptesi) class, installed through MiKTeX. The package `pdfx` is used to produce a PDF/A file for archiveability.

## Thesis presentation slides

The [slides](./slides) are written in LaTeX using the [beamer](https://ctan.org/pkg/beamer) class. The beamer template, contained in the `sty` files, is based on the one provided by PoliTO's DISMA department, available [here](https://didattica.polito.it/laurea_magistrale/ingegneria_matematica/it/template). Follow the [README](./slides/README) for customization.

Speaker notes can be toggled by uncommenting the `\setbeameroption{show notes on second screen}` instruction in the [TeX source](./slides/main.tex). They can then be used during presentations through software such as [pympress](https://github.com/Cimbali/pympress) or [pdfpc](https://pdfpc.github.io/).

## License

This work is authored by Gabriele Degola and licensed under a Creative Commons [«Attribution-NonCommercial-ShareAlike 4.0 International»](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en) license.