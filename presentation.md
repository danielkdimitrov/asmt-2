% Title Presentation
% Adam Smith
% Tilec, Tilburg University



Introduction
================

motivation
----------

- Why are we interested in the wealth of nations?
- seems a bit boring to me


--------

- Ah, we have a new slide here
- we can type latex $x^2_1 + x_2^2 = x_3^2$
- or do an equation environment:

$$
\sum_{i=1}^n x_i^2
$$



A new heading
=================

slide title
-----------

- and we have another slide

   - and nested bullets

- the next slide contains a figure

---------

![](images/quality1.png)

---------

- we can also do a figure from the web

---------


![](http://static01.nyt.com/images/2015/07/24/science/24planet2/24planet2-master675.jpg)




Conclusion
----------

- markdown is a lot of fun
- use a terminal (like the command prompt in Windows) and navigate
  (using "cd" --for "change directory") to the directory with this presentation
- to get the html, type the following on one line:

```
pandoc -s --mathjax --slide-level 2 --toc --toc-depth=1 -t revealjs
presentation.md -V theme=solarized -o presentation.html
```
- if you want a beamer/latex pdf, type:

```
pandoc --slide-level 2 --toc --toc-depth=1 -t beamer
presentation.md -V theme:Montpellier -o presentation.pdf
```
