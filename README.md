# first-example

---
title: "My First RMarkdown Notebook"
author: Shiv Bhakta
date: 24 November 2023
output:
  html_document:
    toc: true
    toc_float: true
    toc_depth: 4
---

# Header 1 {#header_1}

\
Link to [header 2]{#header_2}\
[Bioinformatics](https://training.cam.ac.uk/bioinformatics/event-timetable)

# Header 2 {#header_2}

\
Test[^1].

[^1]: This is the first footnote.

Test number 2[^2].

## List

1.  List of issues\
    a.  Syntax trickery\
        i.  Finicky\
        ii. Not intuitive\
    b.  Utility\
2.  Can't think of any others\

-   Testing bullet points

    -   Testing indents
        -   Testing 2 indents
    -   Testing Backwards

-   And again

-   [x] Checked box\

-   [ ] Unchecked box\
    TABLES

| Col 1    | Col 2    |
|----------|----------|
| Object 1 | Object 2 |

| Left | Centre | Right |
|:-----|:------:|------:|
| Test |  Test  |  Test |

[\^2]: This is the second footnote.

Hello, Website!

For more information about simple R Markdown websites, please read the documentation at <https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html>.

Please also note that simple R Markdown sites are *not* based on **blogdown**. They are probably good for websites with only a few Rmd documents. For larger-scale and more sophisticated websites (such as blogs), you may want to use **blogdown** instead: <https://github.com/rstudio/blogdown>.
