---
title: Introducing GitHub Classroom into a Formal Methods Module

event: FMTea 2024, affiliated with FM 2024, the 26th International Symposium on Formal Methods
event_url: https://fmtea.github.io/

location: Milan, Italy


summary: ''
abstract: 'We have developed an MSc-level module on Formal Methods for Software Engineering with exercises on applying SAT solvers, SMT solvers, Alloy, and nuXmv. In the first iteration of the module, assign- ments were submitted as documents and archive files. Here, we report on our experience of moving the exercises to GitHub Classroom and au- tomating the feedback process through test cases. The main challenges we encountered were related to supporting free-response tasks and de- signing test cases that allow for multiple solutions, provide incremental feedback, and do not encode a solution. We present our setup of exercise repositories, test cases, and feedback report generation. We detail our approach in addressing the challenges of migrating from worksheets to GitHub Classroom and report on survey-based student feedback.'

date: '2024-09-09T00:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-10T00:00:00Z'

authors: [Soaibuzzaman, Jan Oliver Ringert]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

url_code: https://github.com/fm4se/exercises
url_pdf: ./lecture/github-migration/FMTea24.pdf
url_slides: ./lecture/github-migration/FMTea24-Slides.pdf
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

We migrated traditional worksheets from our Formal Methods for Software Engineering module to GitHub Classroom. Our goals were:
- Reduce turnaround time (submission, marking, feedback, resubmission)
- Reduce the number of resubmissions
- Reduce marking effort
- Provide fast and actionable feedback to students during assignments

We describe the migration from regular worksheets to GitHub Classroom in this experience report:

> Soaibuzzaman, Ringert, J.O. [Introducing GitHub Classroom into a Formal Methods Module](./lecture/github-migration/FMTea24.pdf). In: Sekerinski, E., Ribeiro, L. (eds) Formal Methods Teaching. FMTea   2024. Lecture Notes in Computer Science, vol 14939. Springer, Cham. doi: 10.1007/978-3-031-71379-8_2

The [code for the worksheets](https://github.com/fm4se/exercises) is available on GitHub.  
All repositories support autograding via GitHub Classroom. Autograding uses GitHub Actions to run test cases (JUnit) and extract reports from the test results. The tests can be used for feedback when working on the tasks locally (where GitHub Actions are not executed).

