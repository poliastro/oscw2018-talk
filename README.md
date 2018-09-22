# Testing and validation approaches for scientific software

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/poliastro/oscw2018-talk/master?filepath=Talk.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/poliastro/oscw2018-talk/blob/master/Talk.ipynb)

## Description

Nowadays, even though software has a fundamental role in scientific research, the wide majority of scientists is primarily self-taught and received no formal training in software engineering, with often leads to quality and reproducibility problems[1]. The space industry is in a similar situation, with many incident reports describing “various aspects of complacency and a discounting or misunderstanding of the risks associated with software”[2][3].

One of the most useful engineering techniques, software testing, is also the one that presents the biggest gap between its perceived importance and the skill level of scientists in it[4]. Testing, as well as other good practices such as version control and code reviews, not only make code more reusable but also increase the productivity of the developer[5]. However, the special nature of scientific or algorithmic software makes it difficult to apply commonplace testing practices, since the challenges lie in “separating software bugs from model errors and approximation error”[4].

In this talk we will discuss some testing approaches (or lack thereof) present in scientific software that fall short in helping the developers find errors or increase their productivity, and propose some other strategies based on our experience with poliastro, an open source Python library for Astrodynamics[6]. These strategies make use of automated testing frameworks, help covering test cases in an exhaustive way, take advantage of analytical solutions of the problems at hand or public data when available, and guarantee self consistency when there is nothing to compare against. Finally, we will analyze the limitations of these approaches and discuss possible solutions.

Link to contribution:

https://2018.oscw.space/event/1/contributions/13/

## How to use these slides

* Follow the slides online at http://nbviewer.jupyter.org/format/slides/github/poliastro/oscw2018-talk/blob/master/Talk.ipynb

* Launch a executable version using [Google Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/poliastro/oscw2018-talk/blob/master/Talk.ipynb) 

* Launch a live notebook server using [binder](https://beta.mybinder.org/): [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/poliastro/oscw2018-talk/master?filepath=Talk.ipynb)
