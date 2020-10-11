---
layout: post
title: Model Fitting and Report Automation
---

For [this project](https://snprim.github.io/ST558_project_2/), I used bike sharing data to demonstrate model fitting and automating reports. It was yet another opportunity to practice the process of using Github, analyzing data, and communicating results, all of which essential to data science.

I tend to focus on the big picture whenever I start a reasonably big project and want to get the structure ready. For example, for this project, I worked on automating reports before working on the analysis, which resulted in large numbers of files created every time I had one chunk of code completed and long knitting time after each revisions. With some added bad choice of function, I ended up creating a project with a massive number of files (more than 200,000 files!), which made my Rstudio so slow that I had to start over with a new repo and a new R project. When I do a similar project in the future, I would try to break up the task to save memory and running time, either by only using a subset of the data or adding one section at a time. A bottom-up approach of coding will hopefully help me avoid the mistake of creating a massive program from the beginning.

As described above, making sure the program does not grow too massive was a challenge. Programming on one computer is not necessarily hard, but, when the project is linked to a Git repository, the task could be much more complicated and the consideration of memory and scale become more important. For example, besides trying to get the whole structure down, I also made the **fatal** mistake of using two for loops, one of which with a large number of iterations! Nonetheless, although these mistakes cost me many precious hours, they have taught me lessons about efficiency and project building. 

This project gave me several take-aways. Firstly, even when data is small and the program is short, it could grow to an uncontrollable scale very quickly. Understanding how to keep the code efficient and build the code from the bottom up are essential. Secondly, automating the reports is a convenient way to separate results into different reports, fulfilling certain communication goals (such as allowing the audience to focus on one baseball team at a time). 

