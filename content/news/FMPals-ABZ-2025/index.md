---
title: New Dataset and Metrics for Analyzing Alloy Models

event: ABZ 2025 – 11th International Conference on Rigorous State Based Methods
event_url: https://abz-conf.org/site/2025/

location: Düsseldorf, Germany 


summary: ''
abstract: 'Alloy is a modeling language that combines relational first-order logic and temporal logic while providing powerful automated analyses via the Alloy Analyzer. Recent efforts in tool development and teaching of Alloy have contributed the Alloy4Fun dataset enabling many analyses of fine-grained model editing histories.<br>We present a smaller, but complementary dataset of similar editing granularity. While the Alloy4Fun dataset captures users filling in predefined predicates, our dataset is more diverse and users develop all parts of Alloy models including signatures, fields, facts, and commands.<br>We illustrate the differences between the datasets, define a Halstead metric to measure the difficulty of models, and evaluate model revision histories from both datasets on various metrics.'

date: '2025-06-10T00:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-06-10T00:00:00Z'

authors: [Soaibuzzaman, Salar Kalantari, Jan Oliver Ringert]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

url_code: https://github.com/se-buw/alloy-metrics
url_pdf: ./news/fmpals-abz-2025/On-Writing-Alloy-Models-Metrics-and-a-New-Dataset-ABZ25.pdf
url_slides: ./news/fmpals-abz-2025/ABZ25-Slides.pdf
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

We are excited to announce the publication of our new paper, dataset, and accompanying code: [On Writing Alloy Models: Metrics and a New Dataset](./news/fmpals-abz-2025/On-Writing-Alloy-Models-Metrics-and-a-New-Dataset-ABZ25.pdf) presented at [ABZ 2025](https://abz-conf.org/site/2025/)

In this work, we introduce FMPals, a new dataset of Alloy models authored on our Formal Methods Playground. 


### 📁 What We’re Releasing

#### **📄 Paper:**

> Soaibuzzaman, S. Kalantari, J.O. Ringert. On Writing Alloy Models: Metrics and a new Dataset. Rigorous State-Based Methods. ABZ 2025. LNCS 15728, pp. 1–18, 2025.

> [📥 PDF](./On-Writing-Alloy-Models-Metrics-and-a-New-Dataset-ABZ25.pdf)

> 📚 DOI: [10.1007/978-3-031-94533-5_5](https://doi.org/10.1007/978-3-031-94533-5_5)

#### **🗃️ Dataset:**

> Formal Methods Playground Alloy Dataset
> [🔗 Zenodo: https://zenodo.org/records/15619393](https://zenodo.org/records/15619393)

#### **💻 Code & Metrics:**

> Includes our Halstead metric implementation and all scripts for edit path analysis and data processing.
> [🔗 GitHub: https://github.com/se-buw/alloy-metrics](https://github.com/se-buw/alloy-metrics)


### 🧪 Highlights from the Paper

* A new application of **Halstead difficulty metrics** to Alloy.
* Comparison with the Alloy4Fun dataset shows:

  * Broader modeling behaviors in FMPals.
  * Frequent user edits to all language constructs.
  * Iterative and exploratory modeling styles.
* Insights into how users fix errors and how model complexity evolves over time.
