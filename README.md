# Bengali LaTeX Template for Math-Physics Writing
This LaTeX template is designed for academic writing, particularly for subjects involving **mathematical equations and physics**. It is a modified version of Kevin Zhou's template, adapted for Bengali writing support while maintaining its original structure for general academic use. Normal text documents can also be written using this template.
## Files in This Repository

- **bangla_template.zip**: A ZIP archive containing the essential files for this template.
- **custom.sty**: A custom style file modified from Kevin Zhou's original version. This file has been adjusted to support Bengali text.
- **kalpurush.ttf**: The Kalpurush font file, licensed under the [SIL Open Font License, Version 1.0](https://scripts.sil.org/OFL).
- **main.tex**: The main LaTeX file to compile your document. This file is also a modified version of Kevin Zhou's original template.
- **bangla_template.pdf**: A preview PDF of the template.

## How to Use
1. **Download and Upload**  
   - Download the `bangla_template.zip` file from this repository.
   - Upload the ZIP file to [Overleaf](https://www.overleaf.com) to create a new project.

2. **Set the Compiler**  
   - In Overleaf, select **XeLaTeX** as your compiler. This is crucial for proper rendering of both English and Bengali text.
## Writing in Bengali

- The primary language of this template is **English**.
- To enable Bengali text throughout the document, simply use the `\bn` command **once** at the beginning of your document, right after `\begin{document}`:
  ```latex
  \begin{document}
  \bn
  % Now you can start writing Bengali text normally.
  \end{document}

## Credit
This template is originally based on Kevin Zhou's LaTeX template. You can find the original version on his website: [Kevin Zhou's Website](https://knzhou.github.io/)
