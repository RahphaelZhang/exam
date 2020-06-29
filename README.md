# MAST90053 Experimental Mathematics
# Semester 1 Exam

## The University of Melbourne
## School of Mathematics and Statistics

## Due at 3pm AEST on Thursday 2 July 2020

Explanations and annotations are more important than final answers.
The questions may involve a combination of computer work and pen-and-paper work.

You are not allowed to work together or to seek outside help on this exam.

You may use the code in the [subject's repository][repo] as you see fit.

[repo]: https://github.com/aghitza/mast90053

You must yourself write any other code you use (in particular where you are asked to do so, for instance in Question 3).

The exam consists of 3 questions totalling 70 marks.

## The submission process is identical to the one used for the two assignments:

There is one directory per question.

Please insert your solutions and working into the corresponding directory, including enough information so I can assess your work.

In particular:
* I need to be able to run any code that's in your answers or working without having to retype it or go through too many hoops; an easy solution (both for you and for me) is that you attach your Jupyter notebook or Mathematica notebook; just leave them in the default format (from Jupyter: File->Download as->Notebook (.ipynb); from Mathematica: File->Save As->Wolfram Notebook (.nb))
* for explanations, written mathematics, anything else that's not code, do whatever you find most convenient as long as I can look at the result: it can be writing the mathematics in the same Jupyter notebook as the code (some of you are much better than me at this); or typesetting via TeX or similar and including the resulting PDF; or handwriting and taking a photo/scan and attaching that

Don't forget to add your edits to the repository with something like

```
git add sol1.md
git add sol1.ipynb
git commit -m "answers for Question 1"
```

Don't forget to add and commit all changes and push to GitHub before the deadline.
Double-check that everything is okay with

```
git status
```

If it says something like

```
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```

then you are good to go.

I would recommend committing and pushing as you progress through the exam (think of it as smart backup).

## Running Sage

There are about 4 options:
* local installation on your computer
* the [Science server][science]
* my [DigitalOcean server][do]
* [CoCalc][cocalc]

**Please** close and halt notebooks when you're not using them.

Do let me know if you are running into any problems.

[science]: https://mast90053.science.unimelb.edu.au
[do]: https://aghitza.work
[cocalc]: https://cocalc.com
