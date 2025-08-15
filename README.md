## How to open the book

```
conda activate 6.86x
jupyter notebook
```

## How to build the book
```
jupyter-book build .
```

## Where I can list my chapters

Use _toc.yml
```
format: jb-book
root: intro
chapters:
  - file: chapter1
    sections:
      - file: section1
      - file: section2
  - file: chapter2
```

## Enhancement
- We can launch jupiter notebook with [Binder](https://mybinder.org/)