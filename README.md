# Fundamentals of Data Engineering — Lecture Notes

These are my personal study notes for *Fundamentals of Data Engineering* by Joe Reis and Matt Housley (O'Reilly Media, 2022). I'm working through the book chapter by chapter and writing down what I want to remember in my own words — the ideas that stuck, the parts that took a second pass to click, and the connections I made to other reading along the way.

The notes are written for myself, but I'm sharing them publicly because someone else might find them useful as a study companion or a quick reference. They are **not** a substitute for the book.

## What's in this repo

The notes are written in LaTeX and compiled to PDF. The repo contains the source `.tex` files, the figures from the book (referenced under fair-use for personal study), the fonts the build needs, and the compiled PDF.

| File / folder | What it is |
|---|---|
| `main.tex` | Entry point. Brings the preamble and chapter files together. |
| `preamble.tex` | Document setup — geometry, fonts, colours, section styling, callout boxes. |
| `01_preface.tex` | Notes on the book's preface. |
| `02_chapter01.tex` | Notes on Chapter 1 — *Data Engineering Described*. |
| `images/` | Figures from the chapters, with descriptive filenames. |
| `fonts/` | Linux Libertine and Linux Biolinum (used by the build). |
| `Fundamentals_of_Data_Engineering_Notes.pdf` | The compiled output. |

## Volumes

I'm releasing the notes one or two chapters at a time. Each release adds to this repo.

- **Volume I — Preface & Chapter 1 (Data Engineering Described).** ✅ Done.
- **Volume II — Chapter 2 (The Data Engineering Lifecycle).** Coming next.
- **Volume III — Chapter 3 (Designing Good Data Architecture).** Planned.
- ...and so on through the rest of the book.

## Building the PDF

The build uses **XeLaTeX** (for proper Unicode and the OpenType fonts in `fonts/`). On Windows with MiKTeX, TeX Live, or MacTeX:

```bash
xelatex main.tex
xelatex main.tex   # second pass for the table of contents
```

The output is `main.pdf`. I rename it to `Fundamentals_of_Data_Engineering_Notes.pdf` for the release.

## A note on the figures

The figures in `images/` are from the original O'Reilly book. They're included here only so the notes are intelligible without the book open in another window. All credit for the figures and for the underlying content of *Fundamentals of Data Engineering* belongs to Joe Reis, Matt Housley, and O'Reilly Media. If you're studying the field seriously, please buy the book — it's one of the best entry points to data engineering published in the past decade.

The book is available at:
- O'Reilly: <https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/>
- Amazon: ISBN 978-1098108304

## About me

**Mahmoud Salem** — [linkedin.com/in/mahmoudalysalem](https://www.linkedin.com/in/mahmoudalysalem)

I'm working through this book to firm up my own mental model of data engineering. If you spot a mistake or want to discuss something in the notes, feel free to open an issue or reach out on LinkedIn.

## License / fair use

The notes themselves (the prose I wrote in the `.tex` files) are released under the MIT License — use them, adapt them, share them. The book's figures and any direct quotations from the book remain the property of the original authors and publisher and are reproduced here for educational/study purposes only.
