[简体中文](https://github.com/muyuuuu/XDU-report-LaTeX-template/blob/main/README-zh.md)|[English](https://github.com/muyuuuu/XDU-report-LaTeX-template/blob/main/README.md)

# Intro

The latex template of experiment report, XDU. Note: The template is designed by myself which only adds basic items as required by my teacher. So, it's **not official**. I have came here for a month and didn't find a template with specific format. **Don't use this template if your teacher has a clear claim.**

The template's target is simple, applicable and easy to expand, so:

- In `.cls` file, the figure size and font family can be modified easily.
- You can imitate how the current items are added if you want add other items such as supervisor.

Here is the more details of the template: https://muyuuuu.github.io/2020/10/20/XDU-report-LaTeX-template/

# Files structure and compilation method

This code has run in `windows10` and `Arch` successfully, platform is `texlive2020` and compilation is `xelatex +bibtex`.

```
XDU-exp
├─ chapter                                  # The chapters
│    ├─ abstract.tex                            # The abstract
│    ├─ appendix.tex                            # The appendix
│    ├─ conclusion.tex                          # The conclution of experiment
│    ├─ experiment.tex                          # How to set experiment
│    └─ reference.tex                           # The references
├─ figure                                   # The figures
│    ├─ 1.jpg                                   # XDU logo
│    ├─ 2.jpg                                   # Horizontal XDU logo and text
│    ├─ 3.jpg                                   # Vertical XDU logo and text
│    └─ 4.jpg                                   # XDU text
├─ code                                     # The Code files
│    └─ demo.c                                  # A C language demo
├─ books.bib                                # The bib file of reference
├─ main.bbl                                 # The record file of reference
├─ main.pdf                                 # The only file you should submit
├─ main.tex                                 # The main file should be compiled
└─ xdureport.cls                            # The document class
```

# Others

- The font of code is `IBM Plex Mono`, you can download and install it, or replace it with other fixed width font.
- The logo of XDU is from here:  https://xcb.xidian.edu.cn/info/1008/1094.htm
- I am from computer science college so this template may not meet the requirements of other colleges. If there are other suggestions, please new issue or PR.
