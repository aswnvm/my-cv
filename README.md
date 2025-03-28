# My CV

This repository contains my professional CV, designed in LaTeX for a clean and structured layout.

## Features
- Professional and minimalist design
- Easy to update and maintain
- Uses LaTeX for high-quality typesetting

## Installation & Compilation
### Requirements
Ensure you have the following installed:
- [MiKTeX](https://miktex.org/) (or TeX Live)
- [Perl](https://strawberryperl.com/) (Required for `latexindent` formatting)
- [VS Code](https://code.visualstudio.com/) with [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension (optional but recommended)

### Compilation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/aswnvm/cv.git
   cd cv
   ```
2. Compile the LaTeX document:
   ```bash
   pdflatex cv.tex
   ```
   or using VS Code, press `Ctrl + Alt + B` to build.

3. (Optional) Format the document using:
   ```bash
   latexindent -w main.tex
   ```

## Updating Your CV
1. Modify `main.tex` with your latest details.
2. Compile the document as described above.
3. Push changes to GitHub:


## License
This CV template is open for use and modification. Attribution is appreciated but not required.

---

Feel free to modify this README as needed! 🚀
