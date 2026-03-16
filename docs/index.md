--- 
title: "Fundamental Statistics"
author: "Taryn Axelsen"
date: "Last Updated: 2026-03-16"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  Fundamental Statistics Workbook - containing all extra information and exercises.
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


# Preface {-}

<!-- ====== COLOURED BANNER ====== -->
<div style="
  background: linear-gradient(90deg, #e6f0ff, #f7fbff);
  border-left: 8px solid #2a7ae2;
  padding: 22px;
  margin-bottom: 30px;
  border-radius: 6px;
">
  <h2 style="margin-top:0; color:#1a4f8b; font-weight:700;">
    Welcome to <strong>Fundamental Statistics</strong>
  </h2>
  <p style="font-size:1.05em; margin-bottom:0;">
    This Workbook is your companion for the <em>learning through doing</em> component of the course.
    It is designed to guide your practice, deepen your understanding, and support your progress
    throughout the semester.
  </p>
</div>
<!-- ====== END BANNER ====== -->

The primary learning resource for the course is the lectures and tutorials, however we do have an accompanying textbook **De Veaux, Velleman & Bock,
*Stats: Data and Models* (5th edition)**. We do not cover the whole textbook in this
course or in the order it is presented in the book. You are directed to the relevant
readings from the textbook at the end of each chapter within this Workbook.

Once you have watched the lecture recordings, you should consolidate your understanding
by working through the material and tutorials in this Workbook. The textbook
readings will give you further knowledge and help to really solidify the materials
covered each week.

The tutorials align with the modules covered in this course as listed in the Course
Specification. At the end of each tutorial you will notice a Module Checklist and, in
some cases, a Using Statistical software Checklist. Use these checklists to make sure that you have not missed an important concept as you work through the materials.

## 📊 Why Statistics Matters {-}

Statistics helps us make sense of the information we encounter every day.  
At the heart of statistics is **data**, and the need to understand that data is what drives this entire field. The goal in this course
is to give you tools to enable you to competently use and interpret statistics.

<div style="background:#fff4d6; border-left:6px solid #ffb300; padding:18px; margin:25px 0; border-radius:6px;">
  <p style="margin:0; font-size:1.05em;">
    <strong>Think of statistics like a toolbox.</strong><br><br>
    A good toolbox needs a hammer, pliers, a wrench, and a screwdriver.<br><br>
    Likewise, in this course there are some concepts and skills which are essential for you to master - we call these
    <strong>Threshold Competencies</strong>.
    
To pass the course, you’ll need to demonstrate a full understanding of these Threshold Competencies.
  </p>
</div>



Beyond these are the **Expanded Competencies**, which represent the knowledge required to achieve higher than a Pass (P) grade.  

In this Workbook, material related to **Expanded Competencies** are marked with an asterisk (*).

## What This Course Focuses On {-}

The emphasis in Fundamental Statistics is on:

- understanding and developing the basic concepts of statistical reasoning  
- learning to use statistical software  

There is no intention to focus on the particular needs of one or other discipline. That will come later in other courses. Basic statistical concepts are generic. 
Once you understand the core ideas, learning the specialised tools for your field becomes much easier.

We stick fairly closely to the textbook and its approach throughout this course, but for some modules we’ve added **Supplementary Notes** where we felt the textbook did not
covered this particular content in a way that we would prefer (Binomial Model and
Chi-square Test of Independence).

Best wishes and good studying!

## Overall Course Objectives {-}

On completion of this course students should be able to:

* explore relationships in data and distinguish between different methods of
data collection and analysis;

* evaluate and apply a variety of statistical inferential methods to real life situations;

* use a statistical computer package to enter, summarise and analyse data; and

* interpret and communicate the results of statistical analyses for a diverse audience.

## How this book was made {-}

This book was made using **R** [@R-base], and the **bookdown** package [@R-bookdown], which is based on [Markdown](https://en.wikipedia.org/wiki/Markdown) syntax, using **knitr** [@R-knitr].

These tools allow us to build a clean, interactive, and reproducible learning resource.

### Authors{-}

\BeginKnitrBlock{flushright}<p class="flushright">Taryn Axelsen (Springfield, Australia)

Rachel King (Toowoomba, Australia)

Bethany Rognoni (Toowoomba, Australia)</p>\EndKnitrBlock{flushright}


\mainmatter




