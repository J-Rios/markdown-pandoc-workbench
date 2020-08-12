# Markdown Pandoc Workbench

Basic workbench skelleton for plain text based documentation generation.

---

## Notes

- Check [Markdown style guide](https://www.markdownguide.org/cheat-sheet/).

- Check [Pandoc Manual](https://pandoc.org/MANUAL.html).

- Recommended vscode plugins for Markdown work: "markdownlint" and "Pandoc Markdown Preview" (this one allows to see Pandoc compatible Markdown, like multi-line tables. It is better to use this than builtin vscode preview. Ctrl+Shift+R to Open Pandoc Preview Window).

- Use vscode "Pandoc Markdown Preview" plugin (Ctrl+Shift+R) to open a real time preview of Markdown edition.

- The Workbench needs some requeriments, like LaTeX to be able to generate PDF files.

- Run `pandoc_install` (for debian-ubuntu based system) to automatic installation of requeriments:

    ```bash
    sudo ./pandoc_install
    ```

- Generate document in HTML, ODT and PDF formats from Markdown plain text files through `pandoc_run` script:

    ```bash
    ./pandoc_run mydoc_example
    ```

- Clean-Remove generated document files through `pandoc_rm` script:

    ```bash
    ./pandoc_rm mydoc_example
    ```
