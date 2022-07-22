# ErasmusMC PhD Thesis Template

My PhD Thesis created in LaTeX

### Usage

Run `make thesis` to generate the pdf, `make view` to open pdf in okular, and `make watch` to regenerate the pdf on every change.

### Requirements

Ubuntu:

```
sudo apt-get install texlive texlive-xetex latexmk fonts-noto

# optional (needed to be able to use all make commands):
sudo apt-get install inotify-tools okular
```

### Templating Instructions

- Update all of the frontmatter chapters:

  ```
  frontmatter/personalize.tex # Title, author, date, etc.
  frontmatter/cover.tex
  frontmatter/cover-back.tex
  frontmatter/dedication.tex
  frontmatter/foreword.tex
  frontmatter/stellingen.tex
  ```

- And the endmatter

  ```
  endmatter/acknowledgments.tex
  endmatter/colophon.tex
  endmatter/cv.tex
  endmatter/glossary.tex
  endmatter/portfolio.tex
  endmatter/publications.tex
  endmatter/samenvatting.tex
  endmatter/summary.tex
  ```

- `dissertation.tex` contains the chapters / organisation of the thesis, and then `chapters/*.tex` are the relevant chapters which you can use as a template.
- `packages/EMC/style.sty` has some colours that can be adjusted
