---
date: Winter Term 2023
title: Employment Law
subtitle: Cases & Materials 
repo: EmploymentCasebook

version: "Version 1.01"
published: January 2023

author: Eric M. Fink
affiliation: Elon Law School

epigraph: Workin' 9 to 5, what a way to make a livin' \newline Barely gettin' by, it's all takin' and no givin' \newline They just use your mind and they never give you credit \newline It's enough to drive you crazy if you let it \newline 9 to 5, for service and devotion \newline You would think that I would deserve a fair promotion \newline Want to move ahead but the boss won't seem to let me \newline I swear sometimes that man is out to get me
epigraph-author: Dolly Parton
epigraph-source: 9 to 5

casebook: true 

output:
  pdf_document:
    latex_engine: xelatex
    template: master.tex
    path: Casebook.pdf
    pandoc_args: ["--filter=pandoc-sidenote"]

---

\chapter{Preface}

@import "preface.md"

\chapter{Foundations of Employment Law}

@import "chap1.md"

\chapter{Establishing an Employment Relationship}

@import "chap2.md"

\chapter{Scope \& Limits of Employer Control}

@import "chap3.md"

\chapter{Employee Duties to Employers}

@import "chap4.md"

\chapter{Wages \& Hours}

@import "chap5.md"

\chapter{Employee Health \& Safety}

@import "chap6.md"

\chapter{Terminating Employment}

@import "chap7.md"

\chapter{Enforcing Employee Rights}

@import "chap8.md"

\chapter{Recent Developments}

@import "chap9.md"

\chapter{Colophon}

@import "colophon.md"

