---
title: Introducing GitHub Classroom into a Formal Methods Module
date: 2024-09-09
---

We migrated traditional worksheets from our Formal Methods for Software Engineering module to GitHub Classroom. Our goals were:
- Reduce turnaround time (submission, marking, feedback, resubmission)
- Reduce the number of resubmissions
- Reduce marking effort
- Provide fast and actionable feedback to students during assignments

We describe the migration from regular worksheets to GitHub Classroom in this experience report:

> Soaibuzzaman, Ringert, J.O. [Introducing GitHub Classroom into a Formal Methods Module](https://drive.usercontent.google.com/download?id=1lOUPtS6uRowr0kwmNJo9qvb_dHfA3o1r&export=download). In: Sekerinski, E., Ribeiro, L. (eds) Formal Methods Teaching. FMTea   2024. Lecture Notes in Computer Science, vol 14939. Springer, Cham. doi: 10.1007/978-3-031-71379-8_2

The [code for the worksheets](https://github.com/fm4se/exercises) is available on GitHub.  
All repositories support autograding via GitHub Classroom. Autograding uses GitHub Actions to run test cases (JUnit) and extract reports from the test results. The tests can be used for feedback when working on the tasks locally (where GitHub Actions are not executed).

