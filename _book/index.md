--- 
title: "Fundamental Statistics"
author: "Taryn Axelsen"
date: "Last Updated: 2026-03-10"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  This is a minimal example of using the bookdown package to write a book.
  The HTML output format for this example is bookdown::bs4_book,
  set in the _output.yml file.
biblio-style: apalike
csl: chicago-fullnote-bibliography.csl
---
<!-- Peter Dunn: Best way I have found to get correct spacing for units in LaTeX, without screwing up HTML -->
\newcommand{\cms}{\,\text{cm}}
\newcommand{\dLs}{\,\text{dL}}
\newcommand{\xdLs}{\text{dL}}
<!-- No space beforehand so useful in place like \\mgs.\\xdLhas^{-1} -->
\newcommand{\fmols}{\,\text{fmol}}
\newcommand{\ft}{\,\text{ft}}
\newcommand{\gs}{\,\text{g}}
\newcommand{\hs}{\,\text{h}}
\newcommand{\xhs}{\text{h}}
<!-- No space beforehand so useful in place like \\km.\\xhs^{-1} -->
\newcommand{\has}{\,\text{ha}}
\newcommand{\xhas}{\text{ha}}
<!-- No space beforehand so useful in place like \\kgs.\\xhas^{-1} -->
\newcommand{\inches}{\,\text{inches}}
\newcommand{\kgs}{\,\text{kg}}
\newcommand{\kms}{\,\text{km}}
\newcommand{\kWhs}{\,\text{kWh}}
\newcommand{\lbs}{\,\text{lb}}
\newcommand{\Ls}{\,\text{L}}
\newcommand{\xLs}{\text{L}} 
<!-- No space beforehand so useful in place like \\microgs.\\xLs^{-1} -->

\frontmatter
# Preface{-}
Welcome to Fundamental Statistics! 

This Workbook is designed to assist you with the \textit{learning through doing} component of this course. The primary learning resource for the course is the lectures and tutorials, however we do have an accompanying textbook De Veaux, Velleman & Bock,
Stats: Data and Models, fifth edition. We do not cover the whole text book in this
course or in the order it is presented in the book. You are directed to the relevant
readings from the textbook at the end of each chapter within this Workbook. Once
you have watched the lecture recordings, you should consolidate your understanding
by working through the material and tutorials in this Workbook. The textbook
readings will give you further knowledge and help to really solidify the materials
covered each week.

The tutorials align with the modules covered in this course as listed in the Course
Specification. At the end of each tutorial you will notice a Module Checklist and, in
some cases, a Using SPSS Checklist. Use these checklists to make sure that you have
not missed an important concept as you work through the materials. It’s a good idea
to tick them off after completing each module and again at revision time.

Statistics is used regularly to help us gain an understanding of the information
which is available to us on a daily basis. The root of this information is data, and
the need to understand this data is what drives statistics. The goal in this course
is to give you tools to enable you to competently use and interpret statistics. These
statistical tools can be viewed in the same way as everyday household tools.

A toolbox needs to have some basics such as a hammer, pliers, wrench and screwdriver.
Similarly, in this course there are some concepts and skills which are essential
for you to master. We call these Threshold Competencies. In order to pass this course,
you will need to demonstrate that you have full understanding of the \emph{Threshold
Competencies}. Beyond this are what we have labeled Expanded Competencies and
these include what you must know in order to achieve higher than a Pass [P] in the
course. Material that covers these Expanded Competencies will be indicated in this
Workbook by an asterisk *.

The emphasis in Fundamental Statistics is in understanding the basic concepts of
statistical reasoning and learning how to use a statistical software package. There is no intention to focus on the particular needs of one or other discipline. That will
come later in other courses. Basic statistical concepts are generic. Once they are
mastered, learning the language of statistics and specific statistical skills needed for
a particular discipline will not be a major step.

We stick fairly closely to the textbook and its approach throughout this course. It
should be noted that for some modules we have included some Supplementary Notes
in this Workbook. We have included this material because the textbook has not
covered this particular content in a way that we would prefer (Binomial Model and
Chi-square Test of Independence).

The broad objectives of this course are stated below. More detailed overall objectives
are given in the Course Specification. Specific objectives for each module are stated
at the start of each module in the lectures.

Best wishes and good studying!

## Overall Course Objective {-}

On completion of this course students should be able to:
* explore relationships in data and distinguish between different methods of
data collection and analysis;
* evaluate and apply a variety of statistical inferential methods to real life situations;
* use a statistical computer package to enter, summarise and analyse data; and
* interpret and communicate the results of statistical analyses for a diverse audience.

# About{-}

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports; for example, a math equation $a^2 + b^2 = c^2$.

## Usage{-} 

Each **bookdown** chapter is an .Rmd file, and each .Rmd file can contain one (and only one) chapter. A chapter *must* start with a first-level heading: `# A good chapter`, and can contain one (and only one) first-level heading.

Use second-level and higher headings within chapters like: `## A short section` or `### An even shorter section`.

The `index.Rmd` file is required, and is also your first book chapter. It will be the homepage when you render the book.

## Render book{-}

You can render the HTML version of this example book without changing anything:

1. Find the **Build** pane in the RStudio IDE, and

1. Click on **Build Book**, then select your output format, or select "All formats" if you'd like to use multiple formats from the same book source files.

Or build the book from the R console:


``` r
bookdown::render_book()
```

To render this example to PDF as a `bookdown::pdf_book`, you'll need to install XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.org/tinytex/>.

## Preview book{-}

As you work, you may start a local server to live preview this HTML book. This preview will update as you edit the book when you save individual .Rmd files. You can start the server in a work session by using the RStudio add-in "Preview book", or from the R console:


``` r
bookdown::serve_book()
```



