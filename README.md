# Markdown Pandoc Workbench

Basic workbench skelleton for plain text based documentation generation.

---

## Notes

- Check [Markdown style guide](https://www.markdownguide.org/cheat-sheet/).

- Recommended vscode plugins for Markdown work: "markdownlint", "Markdown All in One" and "Pandoc Markdown Preview" (this one allows to see Pandoc compatible Markdown, like multi-line tables. It is better to use than builtin vscode preview. Ctrl+Shift+R to Open Pandoc Preview Window).

- Use vscode "Open Preview" button to show real time Markdown edition.

- The Workbench needs some requeriments, like LaTeX to be able to generate PDF files.

- Run install_requeriments (for debian-ubuntu based system) to automatic installation of requeriments:  
`sudo ./install_requeriments`

- Generate manual in HTML, ODT and PDF formats from Markdown plain text files through "generate_manual" script:  
`./generate_manual`

- Clean-Remove generated manual files through "remove_generated_manual" script:  
`./remove_generated_manual`
