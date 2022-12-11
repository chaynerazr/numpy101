# Numpy for Data Scientist

## Recap
Just in case that you are curious what is mathematic formula for {numref}`unit-circle` of the former [chapter](trying-numpy).

```{math}
:label: pythagorean-formula
\sin^2\theta + \cos^2\theta = 1
```

{eq}`pythagorean-formula` is called Pythagorean formula for sines and cosines. This is probrably the most important identity according to this website from [Clark Univeristy](https://www2.clarku.edu/faculty/djoyce/trig/identities.html). But if you are interested on formula that has important name in it. Those followings are called "Ptolemy's identities".

```{math}
:label: ptolemy-formula1
\sin(\alpha + \beta) = \sin\alpha\cos\beta + \cos\alpha\sin\beta
```
```{math}
:label: ptolemy-formula2
\cos(\alpha + \beta) = \cos\alpha\cos\beta - \sin\alpha\sin\beta
```
```{math}
:label: ptolemy-formula3
\sin(\alpha - \beta) = \sin\alpha\cos\beta - \cos\alpha\sin\beta
```
```{math}
:label: ptolemy-formula4
\cos(\alpha - \beta) = \cos\alpha\cos\beta + \cos\alpha\sin\beta
```
```{margin} More formula for Trigonometry
Please visit [Dave's site](https://www2.clarku.edu/faculty/djoyce/trig/identities.html). There is a compilation there!
```

## Numpy with Pandas
```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/0/0f/Grosser_Panda.JPG/2880px-Grosser_Panda.JPG
---
height: 300px
name: real-panda
---
Is it about me?
```

No no.. This is not about {numref}`real-panda` but aboout a library [pandas](https://pandas.pydata.org/) that uses by data scientist to deal with huge amount of data.

Pandas introduce the concept of dataframe and operation on it facilitate the analysis of big data.

```python
df = pd.DataFrame({"A":[12, 4, 5, 44, 1],
                   "B":[5, 2, 54, 3, 2], 
                   "C":[20, 16, 7, 3, 8],
                   "D":[14, 3, 17, 2, 6]})
```

From the code above, the data frame is created with 4 columns: A, B, C and D. as shown in {numref}`dataframe`.

```{figure} https://media.geeksforgeeks.org/wp-content/uploads/1-551.png
---
height: 200px
name: dataframe
---
Dataframe with 4 columns
```

We can calculate mean of each column with code which return result as {numref}`mean`

```python
df.mean(axis = 0)
```
```{margin} Learn more about Pandas
Code and pictures explaining here is actually from [geeksforgeeks.org](https://www.geeksforgeeks.org/python-pandas-dataframe-mean/). Please visit them to learn more!
```
```{figure} https://media.geeksforgeeks.org/wp-content/uploads/1-561.png
---
height: 200px
name: mean
---
Means of each colums of data frame
```
You can see that it's quite convinient to find the means or multiple columns on just one command. This is why Pandas is the essential tools for data scientists.


In the next chapter, we will explore how numpy and pandas work together.


