---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

---
# bayesfm
Python package to run [Bayesian Fama-MacBeth Regressions from Bryzgalova, Huang & Julliard (2024)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4989615).
As presented by the authors, this methodology provides reliable risk premia 
estimates for both tradable and nontradable factors, detects those weakly 
identified, delivers valid credible intervals for all objects of interest, and 
is intuitive, fast and simple to implement. You can view `bayesfm` on 
[PyPi](https://pypi.org/project/bayesfm/) 
or 
[GitHub](https://github.com/gusamarante/bayesfm)

---
# DSGEpy
This is a Python library to specify, calibrate, solve, simulate, estimate and 
analyze linearized DSGE models. The specification interface is inpired by 
dynare, which allows for symbolic declarations of parameters, variables and 
equations. This library is an effort to bring the DSGE toolset into the 
open-source world in a full python implementation.

You can find more details about on [dsgepy.com](http://dsgepy.com)

---
# pyAA
This repository was born as a quantitative finance project during my studies 
for the CQF, but it ended up as  an all-around finance project. You can find 
it [here](https://github.com/gusamarante/pyaa).

---
# pyacm
Implementation of ["Pricing the Term Structure with Linear Regressions" from Adrian, Crump and Moench (2013)](https://www.newyorkfed.org/medialibrary/media/research/staff_reports/sr340.pdf).
This library prices the time series and cross-section of the term structure of 
interest rates using a three-step linear regression approach. Computations are 
fast, even with a large number of pricing factors. Generates estimates for term 
premium, risk neutral yields and expected returns. You can view `pyacm` on 
[PyPi](https://pypi.org/project/pyacm/) 
or 
[GitHub](https://github.com/gusamarante/pyacm)
