---
title: New Dataset and Metrics for Analyzing SMT-LIB Scripts

event: SMT 2025 – 23rd International Workshop on Satisfiability Modulo Theories
event_url: https://smt-workshop.cs.uiowa.edu/2025/

location: Glasgow, UK


summary: ''
abstract: 'Satisfiability Modulo Theory (SMT) checking is concerned with checking the satisfiability of first-order formulas with respect to some background theories. The SMT-LIB format is a standardized language for scripts expressing SMT problems.<br>Popular datasets of SMT-LIB scripts have been collected for benchmarking SMT solvers. Rather than focusing on evaluating SMT solvers, our work focuses on exploring how novice users write SMT-LIB scripts. We present a dataset of SMT-LIB scripts with fine-grained editing paths. The dataset consists of 2,415 editing paths with a total of 18,133 SMT-LIB scripts. All scripts were collected from a web-based interface for the Z3 SMT solver in educational settings.<br>We analyze the dataset in terms of sizes of scripts, errors users make, similarities of consecutive scripts, editing distances, and edit steps required to fix errors. We make the dataset and the code for computing our metrics available for future research on language design, tool support, and teaching materials.'

date: '2025-08-10T00:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-08-10T00:00:00Z'

authors: [Soaibuzzaman, Jan Oliver Ringert]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

url_code: https://github.com/se-buw/smt-metrics
url_pdf: ./news/fmpsmt-smt-2025/On-Writing-SMT-LIB-Scripts-Metrics-and-a-New-Dataset-SMT25.pdf
url_slides: ./news/fmpsmt-smt-2025/OnWritingSMTScripts.pdf
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [FM Playground]
---

We are excited to announce the publication of our new paper, dataset, and accompanying code: [On Writing SMT-LIB Scripts: Metrics and a New Dataset](./news/fmpsmt-smt-2025/On-Writing-SMT-LIB-Scripts-Metrics-and-a-New-Dataset-SMT25.pdf) presented at [SMT 2025](https://smt-workshop.cs.uiowa.edu/2025/)

In this work, we introduce FMPsmt, a new dataset of SMT-LIB Scripts authored on our Formal Methods Playground. 


### 📁 What We’re Releasing

#### **📄 Paper:**

> Soaibuzzaman, J.O. Ringert. On Writing SMT-LIB Scripts: Metrics and a New Dataset. International Workshop on Satisfiability Modulo Theories. SMT 2025. CEUR 4008, pp. 91–102, 2025.

> [📥 PDF](./On-Writing-SMT-LIB-Scripts-Metrics-and-a-New-Dataset-SMT25.pdf)

> 📚 URL: [https://ceur-ws.org/Vol-4008/SMT_paper15.pdf](https://ceur-ws.org/Vol-4008/SMT_paper15.pdf)


#### **🗃️ Dataset:**

> Formal Methods Playground SMT Dataset
> [🔗 Zenodo: https://zenodo.org/records/15488371](https://zenodo.org/records/15488371)

#### **💻 Code & Metrics:**

> Includes all scripts for edit path analysis and data processing.
> [🔗 GitHub: https://github.com/se-buw/smt-metrics](https://github.com/se-buw/smt-metrics)
