#Improving Series Expansions Module in SymPy

### About Me :
##### Contact Information :
 - **Name** : Arif Ahmed
 - **University** : [Birla Institute of Technology and Science, Pilani](http://www.bits-pilani.ac.in/)
 - **Short Bio** : Student of MSc(Hons)Mathematics and B.E(Hons)Computer Science
 - **Email-Id** : arif.ahmed.5.10.1995@gmail.com
 - **GitHub username** : [ArifAhmed1995](https://github.com/ArifAhmed1995)
 - **Time-Zone** : UTC + 5:30
##### Personal Information :
My name is Arif Ahmed, a second year undergraduate student at BITS Pilani Goa Campus,India. Currently I am pursuing a degree in Mathematics and Computer Science.

I use Linux Mint 18 on my workstation and PyCharm IDE for any Python related work.I have been coding in Python(more than a year),Java(> 2 years), C/C++(more than a year) and R(about a year).I like Python the best of all the languages mentioned because it's easier to work with as compared to the others.

Along with Mathematics courses such as Complex Analysis, Discrete Mathematics, Optimization, Introduction to Algebra, Real Analysis, etc I have also completed various online courses related to Computer Science and Programming.

###### The online courses successfully completed are :
 - [Algorithms I - Princeton University](https://www.coursera.org/learn/algorithms-part1)
 - [Introduction to Interactive Programming in Python(Part I) - Rice University](https://www.coursera.org/learn/interactive-python-1)
 - [Introduction to Interactive Programming in Python(Part II) - Rice University](https://www.coursera.org/learn/interactive-python-2)
 - [Principles of Computing(Part I) - Rice University](https://www.coursera.org/learn/principles-of-computing-1)
 - [Principles of Computing(Part II) - Rice University](https://www.coursera.org/learn/principles-of-computing-2)
 - [First Five Courses of Data Science Specialization - Johns Hopkins University](https://www.coursera.org/specializations/jhu-data-science)

As part of the above courses I had to code various weekly assignments in Java, Python and R.The most exciting assignments were the ones in Rice University's courses. Unfortunately I cannot upload the assignments on GitHub as the instructors forbade us to do so. In my freshman year, I made a simple simulator in Java which simulates [Diffusion of a Gas](https://github.com/ArifAhmed1995/Mini-Projects/blob/master/Simulation.java).

Ever since I was introduced to Python, I liked it far better than any other language. The reason is that one can think more about converting ideas to working code rather than wrestling around with the nuances of the language.One of the advanced features about Python that I liked was the `lambda` operator/function.It's a nifty way to create a nameless function.

One the best features I like about SymPy is it's capability to solve difficult integration problems, especially Indefinite Integrals :

```
>>> Integral(x**3*sin(x*2), x).doit()
-x**3*cos(2*x)/2 + 3*x**2*sin(2*x)/4 + 3*x*cos(2*x)/4 - 3*sin(2*x)/8
```

### Contributions :
I stumbled upon SymPy while searching for Mathematics related projects on GitHub, sometime around 20th September 2016.I have attempted to fix issues and understand SymPy's codebase since then.Here is a list of my pull requests :

##### Merged:
 - [Geometric sum evaluates correctly for float base](https://github.com/sympy/sympy/pull/11682) **(Simple Fix)**
 - [matrices : re and im works for matrices](https://github.com/sympy/sympy/pull/11696)
 - [core.evaluate : evaluate(False) works for numeric operators](https://github.com/sympy/sympy/pull/11714)
 - [evalf : Increase depth of symbolic evaluation for Abs()](https://github.com/sympy/sympy/pull/11970)
 - [solvers/solveset: Rectify solution for some special equations](https://github.com/sympy/sympy/pull/12040)
 - [ntheory : Add functionality to return list of all factors](https://github.com/sympy/sympy/pull/12194)
 - [integrals : Add singularity test for Zero denominator](https://github.com/sympy/sympy/pull/12142)
 - [core : Float constructor allows to set binary or decimal precision](https://github.com/sympy/sympy/pull/12227)

##### Unmerged :
 -  [matrices:Matrix**exponent stays unevaluated for non-integer exponent](https://github.com/sympy/sympy/pull/11648) **(Needs Decision)**
 -  [matrices : Add an optional key 'evaluate' for MatPow.](https://github.com/sympy/sympy/pull/11843) **(Needs Decision)**
 -  [[WIP]sympify : Added support for translating basic numpy datatypes](https://github.com/sympy/sympy/pull/11666)
 -  [Matrix : transpose of non-complex symbol returns the same symbol](https://github.com/sympy/sympy/pull/11733)
 -  [solve : Solutions with spurious real/imaginary terms are discarded)](https://github.com/sympy/sympy/pull/11815)
 -  [Add contour plot function](https://github.com/sympy/sympy/pull/12049)
 -  [vector : Add Laplacian and Vector Laplacian support](https://github.com/sympy/sympy/pull/12261)
 -  [ring series : rs_series extended for logarithm](https://github.com/sympy/sympy/pull/12274)

###Theory :
A series
