# Markdown Pandoc Workbench

Markdown Pandoc Workbench for plain text based documentation generation.

---

## Requeriments

Give execution permission and run `pandoc_install` script (for debian-ubuntu based system) to automatic installation of all requeriments:

```bash
chmod +x pandoc_install pandoc_run pandoc_rm
sudo ./pandoc_install
```

## Usage

To generate documents in HTML, ODT and PDF formats from Markdown plain text files, use the `pandoc_run` script:

```bash
./pandoc_run mydoc_example
```

To clean-remove generated documents files, use the `pandoc_rm` script:

```bash
./pandoc_rm mydoc_example
```

## Notes

- Check [Markdown style guide](https://www.markdownguide.org/cheat-sheet/).

- Check [Pandoc Manual](https://pandoc.org/MANUAL.html).

- Recommended vscode plugins for Markdown work:

    - **markdownlint:** To check for correct Markdown style.

    - **Pandoc Markdown Preview:** Allows to see Pandoc compatible Markdown, like multi-line tables. It is better to use this than builtin vscode preview due there is some things that are not supported in builtin previes (i.e. multi-line tables). Ctrl+Shift+R to Open Pandoc Preview Window.

    - **Language - Code Spell Checker:** To check for correct english/spanish/etc. text and avoid misspelling.

- Use vscode "Pandoc Markdown Preview" plugin (Ctrl+Shift+R) to open a real time preview of Markdown edition.

- The Workbench needs some requeriments, like LaTeX to be able to generate PDF files.
