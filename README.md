# Official Unofficial LaTeX Template for Emory University (Laney Graduate School) Dissertations

There were several unofficial LaTeX templates floating around when I started writing my dissertation. They mostly got passed down from one graduate student to the next. Naturally, the templates all differed slightly and there was a lot of ugly LaTeX accumulating in the preamble. I decided to make an **official** unofficial template that abides by the ETD guidelines and was free of preamble bloat. This template is heavily based on another by Mckenzie Rachel West. It follows the ETD guidelines as of Spring 2019.

You can find this template on [Overleaf](https://www.overleaf.com/latex/templates/emory-laney-graduate-school-dissertation-template/hjszzmrwswkv).

## How to use this template
1. Add the details about your dissertation in the `INFORMATION` section of `./main.tex`
2. Place packages and custom commands in `formatting/custom.tex`
4. Write your abstract in `special-pages/abstract.tex`
5. Place references in `references.bib`
6. Each chapter should be a separate `.tex` file in the `./chapters` directory. Be sure to `\input{}` your new chapters in the `CHAPTERS` section of `./main.tex`
7. Place figures in the `./figures` directory
8. Write your acknowledgements in `special-pages/acknowledgements.tex` (optional)
