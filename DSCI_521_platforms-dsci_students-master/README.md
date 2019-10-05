# DSCI 521: Computing Platforms for Data Science

How to install, maintain, and use the data scientific software "stack". The Unix operating system, integrated development environments, and problem solving strategies.

__Slack Channel__: [#521_platforms-dsci](https://ubc-mds.slack.com/app_redirect?channel=521_platforms-dsci)

## Class Meetings

This course occurs during __Block 1__ in the 2019/20 school year.

__Lectures__: Mondays and Wednesdays, 9:00-10:30, in DMP 110. [See the [MDS calendar](https://ubc-mds.github.io/calendar/)]

__Labs__: 

- Section 1: Monday, ORCH 3018, 14:00-16:00
- Section 2: Tuesday, ORCH 4018, 14:00-16:00
- Section 3: Wednesday, ORCH 3016, 14:00-16:00

In addition, we'll see you during a special time slot for your last quiz -- see quiz details for more information. 

## Course Learning Outcomes

By the end of the course, students are expected to:
1. Use the Unix command line to navigate their computer's filesystem.
2. Define and distinguish between absolute file paths and relative file paths.
3. Effectively use local and remote version control software (e.g., Git and GitHub) to organize projects and manage file versions.
4. Create, edit and run reproducible literate Python and R code documents (e.g., reports and presentations) using Jupyter and RMarkdown. 
5. Write and edit Markdown and in-line LaTeX syntax within literate code documents. 
6. Define and correctly use a project working directory.
7. Diagnose and troubleshoot programming and development environment problems, and explain how such problems can be avoided.
8. Write regular expressions for pattern matching.
9. Set and get environment variables;

## Teaching Team

At your service!

| Position           | Name    | Slack Handle | GHE Handle | Office hours |
| :----------------: | :-----: | :----------: | :--------: | :----------: |
| Lecture & Lab Instructor | Rodolfo | `@rodolfo`   | `@lourenzu` | 16:00 - 17:00 on Wednesdays in ICCS 359|
| Teaching Assistant | Freddy Francis | `@Freddy Francis`| - | 12:15 - 13:15 on Mondays in ESB 1045 |
| Teaching Assistant | Javier Castillo-Arnemann | `@Javier Castillo-Arnemann` | - | 13:00 - 14:00 on Fridays in ESB 1045 |
| Teaching Assistant | Loren Oh  | `@Loren Oh`  | - | 13:00 - 14:00 on Tuesdays in ESB 1045 |
| Teaching Assistant | Ozum  | `@ozum`  | - | - |
| Teaching Assistant | Doris Xiang  | `@Doris Xiang`  | - | - |

*note - Attendance at office hours is optional* 

## Assessments

This is an __assignment-based course__. You'll be evaluated as follows:

| Assessment        | Weight  | Due Date           | Location |
|-------------------|---------|--------------------|----------|
| MDS Policies quiz | 5%      | 2019-09-13 @ 17:00 | [Canvas](https://canvas.ubc.ca/courses/40620) |
| Lab 1             | 13%     | 2019-09-14 @ 18:00 | Submit to Github |
| Lab 2             | 14%     | 2019-09-21 @ 18:00 | Submit to Github |
| Quiz 1            | 20%     | 2019-09-23 @ 14:00 | Your lab room | 
| Lab 3             | 14%     | 2019-09-28 @ 18:00 | Submit to Github |
| Lab 4             | 14%     | 2019-10-05 @ 18:00 | Submit to Github |
| Quiz 2            | 20%     | 2019-10-10 @ 11:00 | DMP 110 |

Tip: Use the lecture learning objectives as beacons when studying for your quizzes!

| Lecture | Topic | Readings |
|:-------:|-------|--------------|
| 1 | [Introduction to MDS tools (Unix, Git/GitHub, Jupyter)](https://github.ubc.ca/MDS-2019-20/DSCI_521_platforms-dsci_students/blob/master/lectures/01_lecture-intro-MDS-tools/01_lecture1-intro-MDS-tools.ipynb)| <ul><li>[The Unix Shell: Navigating Files and Directories](https://swcarpentry.github.io/shell-novice/02-filedir/index.html) or [The shell](http://happygitwithr.com/shell.html)</li><li>[Introduce yourself to Git](http://happygitwithr.com/hello-git.html)</li><li>[Connect to GitHub](http://happygitwithr.com/push-pull-github.html)</li><li>[Jupyter Lab Documentation](https://jupyterlab.readthedocs.io/en/stable/)</ul> |
| 2 | Getting groovy with Git and GitHub | <ul><li>[Excuse me, do you have a moment to talk about version control? by Jenny Bryan](https://peerj.com/preprints/3159/)</li><li>[Comparing commits across time](https://help.github.com/articles/comparing-commits-across-time/)</li><li>[Resolving a merge conflict using the command line](https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/)</li><li>[nbdime – diffing and merging of Jupyter Notebooks](https://nbdime.readthedocs.io/en/stable/)</li></ul>  |
| 3 | More Git, as well as mark-up languages, webpage basics and GitHub Pages  | <ul><li>[.gitignore](https://www.atlassian.com/git/tutorials/saving-changes/gitignore)</li><li>[Fork a repo](https://guides.github.com/activities/forking/)</li><li>[Set up keys for SSH for use with GitHub](http://happygitwithr.com/ssh-keys.html)</li><li>[Getting Started with GitHub Pages](https://guides.github.com/features/pages/)</li><li>[Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)</li><li>[HTML cheat sheet](https://www.w3schools.com/html/default.asp) (reference)</li><li>[LaTeX cheat sheet](http://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf) (reference)</li></ul> |
| 4 | Introduction to RStudio and RMarkdown | <ul><li>[R Markdown Cheat Sheet](https://rmarkdown.rstudio.com/lesson-15.html) (reference) </li><li>[R Markdown Reference Guide](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf) (reference) </li><li>[R Markdown lessons from RStudio](https://rmarkdown.rstudio.com/lesson-1.html)</li><li>[R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) (reference)</li><li>[R Markdown code chunk options](https://yihui.name/knitr/options/) (reference)</li></ul>  |
| 5 | Using Jupyter notebooks and RMarkdown to create professional and reproducible presentations | <ul><li>[R Markdown presentations with ioslides](https://rmarkdown.rstudio.com/ioslides_presentation_format#overview)</li><li>[R Markdown presentations with xaringan](https://bookdown.org/yihui/rmarkdown/xaringan.html)</li><li>[Jupyter presentations with RISE](https://damianavila.github.io/RISE/)</li></ul> |
| 6 | Let's talk about filenames and Data Science project organization | <ul><li>[Good Enough Practices in Scientific Computing](https://swcarpentry.github.io/good-enough-practices-in-scientific-computing/)</li> <li>[Regex](https://regexone.com/lesson/introduction_abcs)</li><li>[Regex test](https://regex101.com)</li><li>[Practicing Regex](https://regexcrossword.com/)</li></ul>|
| 7 | RStudio projects and driving Git from RStudio | <ul><li>[Using RStudio Projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)</li><li>[Connect RStudio to Git and GitHub](http://happygitwithr.com/rstudio-git-github.html)</li><li>[Workflow: projects](http://r4ds.had.co.nz/workflow-projects.html)</li></ul> |
| 8 | Reading the docs & getting help | <ul><li>[Three tips for posting good questions to R-help and Stack Overflow](https://www.r-bloggers.com/three-tips-for-posting-good-questions-to-r-help-and-stack-overflow/)</li><li>[How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve)</li></ul> |

## Attributions

Materials were inspired, re-used and re-mixed from the following sources:
- [Software Carpentry](https://software-carpentry.org/), specifically the Unix Shell and Git lessons
- [Happy Git and GitHub for the useR by Jenny Bryan and the STAT 545 TAs](http://happygitwithr.com/)
- [Data 8: The Foundations of Data Science](http://data8.org/), specifically Lab 01
- [Data Carpentry Reproducible Science Workshop](https://datacarpentry.org/rr-organization1/)
