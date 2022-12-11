# Welcome to Numpy101

(introduction-h2)=
## Introduction

This book is inspired by [Python101](https://python101.ml/intro.html) to explain how (numpy)[https://numpy.org/] fit in data scient. The **Python101** book is quite cute that you can see from their front page:

```{figure} images/python101_frontpage.png
---
height: 300px
name: python101-frontpage
---
Python101 is so cute!! 
```

Many content here is just from default content when you run the following commands. 

```shell
jupyter-book create my-book/
```

This required you to have install python package from [Jupuyter Book](https://jupyterbook.org/en/stable/intro.html) that you can install it by
```shell
conda install -c conda-forge jupyter-book
```

and it can 

The book is the final assignment from the course [The Data Science Toolbook](https://extendedlearning.ubc.ca/courses/data-science-toolbox/fs041) which only intentionally teach how to use tool related to data scientt but it should not be graded against the quality of contents inside it but only on how I can demonstrate using Jupyter Book, Jupeter Notebook to create an online booe. So, please read the [](disclaimer-h2) carefullly.

(disclaimer-h2)=
## Disclaimer & Apology

As mentioned in [](introduction-h2), this book is just an assignment, so please don't take the content of this book seriously. I cannot be responsible for the damange that this book done if you really follow stuff here.

I also want to apologise for spelling & english gramartically mistake on this book. This include using informal language and being very non-academic. And from time to time you might get shown the unrelated picture of Jupiter like this:
 
```{figure} https://solarsystem.nasa.gov/system/resources/detail_files/2486_stsci-h-p1936a_1800.jpg
---
height: 300px
name: jupiter-figure
---
The beautiful planet Jupiter!
```
By the way, the {numref}`jupiter-figure` is just getting from item 3 of module 8 of the course.

And finally, I hope you enjoy this journey.

### So, What is numpy, you asked?

```{margin} I am not sure what I should write here?
Maybe just nothing...
```

Basically, it's just a library that have collection of mathematic opertions. For example, if you want to calculate to fine `x` in the following formula.

```{math}
:label: sine
x=\sin(\frac{\pi}{2})
```

From {eq}`sine` above, Python code is:

```python
x = np.sin(np.pi/2)
```

or this formala which show the relation ship between $\sin$ , $\cos$ and $\tan$.

```{math}
:label: tangent
\tan x  = \frac{\sin x}{\cos x}
```

Again, from {eq}`tangent`, this can be done in Python code.

```python
np.tan(x) == np.sin(x)/np.cos(x)
```

### Then, what next

This following is table of contents of this book.
```{tableofcontents}
```
