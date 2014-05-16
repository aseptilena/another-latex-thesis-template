# another-latex-thesis-template

Another LaTeX thesis template, for a master's or Ph.D. thesis or dissertation.

**Compiled document: [Thesis.pdf](./Thesis.pdf?raw=true)**

**Sample pages (click to enlarge):**

<img height="225" src="./Miscellaneous/Screenshot-01.png?raw=true" alt="Screenshot 01">
<img height="225" src="./Miscellaneous/Screenshot-02.png?raw=true" alt="Screenshot 02">
<img height="225" src="./Miscellaneous/Screenshot-03.png?raw=true" alt="Screenshot 03">
<img height="225" src="./Miscellaneous/Screenshot-04.png?raw=true" alt="Screenshot 04">
<img height="225" src="./Miscellaneous/Screenshot-05.png?raw=true" alt="Screenshot 05">
<img height="225" src="./Miscellaneous/Screenshot-06.png?raw=true" alt="Screenshot 06">
<img height="225" src="./Miscellaneous/Screenshot-07.png?raw=true" alt="Screenshot 07">
<img height="225" src="./Miscellaneous/Screenshot-08.png?raw=true" alt="Screenshot 08">

## Main Features

- Simple template that can be further customized or extended.
- Consistent style for figures and tables.
- Consistent style for mathematical theorems, definitions, lemmas, etc.
- Template document contains numerous examples.

## Overview

The main LaTeX source file is `Thesis.tex`; the compiled document is `Thesis.pdf`.

Instructions for compiling the document (TEX &rarr; DVI &rarr; PDF):

- **Method 1:** Use latexmk for fully automated document generation:
	- `latexmk -e "$dvipdf='dvipdfm %O -o %D %S'" -pdfdvi "Thesis.tex"`

- **Method 2:** Use latex, bibtex, and dvipdfm manually:
	- `latex "Thesis.tex"`
	- `bibtex "Thesis"`
	- `latex "Thesis.tex"` (run multiple times to resolve cross-references)
	- `dvipdfm "Thesis.dvi"`

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
