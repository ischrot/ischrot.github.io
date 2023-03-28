---
layout: page
title: Seminar Special Topics in Continuous Optimization and Optimal Control (SS 23)
description: >
  Here you find information about the seminar on Special Topics in Continuous Optimization and Control in the summer semester 2023.
hide_description: false
sitemap: true
---

<!-- invert_sidebar: true -->

2023-03-28
{:.note title="Last modified at"}

0. I need this empty list to make the TOC work
{:toc}

## General Information

Organizers
: - [Prof. Dr. Ekaterina A. Kostina][ekaterina]
  - [Ihno Schrot][ihno]
  - [Marta Sauter][marta]
  
  Please contact [Ihno Schrot][ihno] if you have questions regarding this seminar.
  {:.note title="Contact"}

Kick-Off Meeting Date
: *TBA*

<!-- Tuesday, April 26, 11:15, in SR1 (INF 205) -->

Date
: Mondays, 14:15 - 15:45

Room
: Seminarroom 2 (SR 2) in INF 205 
  
  We meet in person.
  {:.note}

Level:
: Master Students (Bachelor students with relevant experience and motivation are welcome, too, though!)

Language
: English

Requirements
: You should have attended at least the following courses:
    - Analysis 1, 2
    - Linear Algebra 1
    - Nonlinear Optimization

  You can of course still join the seminar if you are missing one of these courses, but we strongly recommend that you attend the missing course in parallel then. The experience is that students without knowledge in these areas have problems with the topics of this seminar.
  {:.note}
  
Registration
: To participate in the seminar, please register for the seminar on [MÜSLI][muesli]. The number of participants is limited to 18.

## Kick-Off Meeting
The kick-off meeting takes place on *TBA*. Here, we 
  - discuss organizational matters,
  - form pairs if necessary,
  - **distribute** the topics,
  - discuss the schedule.

## Topics

The following topics are only preliminary!
{:.note title="Important"}

We have talks from three different fields on offer. We will agree on a field in the [kick-off meeting][kom]. Literature suggestions can be found [below][lit].

### Methods for Nonlinear Optimization Problems

1. CG-Methods
2. Penalty and Augmented Lagrangian methods
3. SQP with Indefinite Hessian Approximations
4. BFGS-SQP Method for Nonsmooth, Nonconvex, Constrained Optimization
5. Interior-Point Filter Line-Search Algorithm for NLP
6. Global Optimization Methods
7. Robust Nonconvex Optimization

### Optimization for Data Science
1. Subgradient Methods
2. Mirror Descent
3. Proximal Gradient Methods
4. Accelerated Gradient Methods
5. Smoothing for Nonsmooth Optimization

### Model Order Reduction
1. Proper Orthogonal Decomposition (POD)
2. Empirical Interpolation Method (EIM)
3. Reduced Basis Methods (RB)
4. Dynamic Mode Decomposition (DMD)
5. Derivative Extended POD (DEPOD)
6. Balanced Truncation
7. Rational Interpolation

## Goal of the Seminar
> **Teach** your fellow students your topic in an understandable yet professional way!
{:.lead}

## Expectations
In order to complete the seminar successfully you have to
  - attend the weekly meetings,
  - prepare and do a presentation of 90min (+10min discussion) in pairs <!--*or* 45min (+5min discussion) alone.-->

You do not need to write an essay.
{:.note}

Further we expect
  - a thorough understanding of your topic,
  - professional display and communication of Mathematics,
  - scientific literature work,
  - a professional presentation (the presentation technique is up to you).

## Schedule

| Date | Topic | Speaker(s) |
|------|-------|------------|
| *TBA* | Kick-off meetig | None |


<!-- | May 24th | Active set methods for NLPs with vanishing constraints | Laura |
| May 31st | A dual Newton strategy for the efficient soulution of sparse QPs arising in SQP-based nonlinear model predictive control | Jörn, Szymon | -->

<!-- | None | Robust nonconvex optimization | None | -->
The speakers will be decided in the [kick-off meeting][kom].
{:.note}

## Grading

We primarly rate your talks based on [this rubric][rubric].

## Literature 

We expect you to identify and use further literature if necessary on your own! The following literature suggestions are to be understood as starting points.
{:.note title="Important"}

You find all the following literature online when you are connected to the University network. If you are not in the University, you can connect to the network using the VPN. You find information on the VPN [here][vpn].
{:.note}

### Methods for Nonlinear Optimization Problems
General recommendations
: - Nocedal, Jorge, and Stephen J. Wright, eds. Numerical optimization. New York, NY: Springer New York, 2006.
  - Ulbrich, Michael, and Stefan Ulbrich. Nichtlineare Optimierung. Springer-Verlag, 2012.
    
Recommendations by topics
: CG-Methods
  : - J. Nocedal, S.J. Wright. Numerical Optimization, Springer, 2006. Ch. 5, pp. 101–133.
    - Published papers about new research results on the field of nonlinear CG-methods
  
  Penalty and augmented Lagrangian methods
  :   -  J. Nocedal, S.J. Wright. Numerical Optimization, Springer, 2006. Ch. 17, pp. 497–527.
  
  SQP with indefinite Hessian approximations
  :   - D. Janka. Sequential quadratic programming with indefinite Hessian approximations for nonlinear optimum experimental design for parameter estimation in differential–algebraic equations. PhD Thesis. Heidelberg. (2015).
      - D. Janka, C. Kirches, S. Sager and A. Wachter. An SR1/BFGS SQP algorithm for nonconvex nonlinear programs with block-diagonal Hessian matrix (2016).
      
  BFGS-SQP Method for nonsmooth, nonconvex, costrained optimization
  :   - F.E. Curtis et. al. BFGS-SQP Method for nonsmooth, nonconvex, constrained optimization and its evaluation using relative minimization profiles. Optimization Methods and Software (2017)
  
  Interior-point filter line-search algorithm for NLP
  :   - A. Wachter and L.T., Biegler. On the implementation of an interior-point filter line-search algorithm for large-scale nonlinear programming. Math. Program., Ser. A (2005).
      
  Global optimization methods
  :   - C.S. Adjiman et. al. A global optimization method, $$ \alpha $$ BB, for general twice-differentiable constrained NLPs - I. Theoretical advances.
Computers Chem. Engng Vol.2 No. 9, pp. 1137-1158. (1998).
      - C. A. Meyer and C. A. Floudas. Convex underestimation of twice continuously differentiable functions by piecewise quadratic pertubation: spline $$ \alpha $$ BB underestimators.
  
  Robust nonconvex optimization
  :   -  B. Houska. Robust Optimization of Dynamic Systems. Chapter 3-4. (2011).
  
### Optimization for Data Science

Subgradient Methods
: - Sor, Naum Z., Minimization methods for non-dierentiable functions, Springer (Berlin),
1985 (in particular chapters 1,2, 4; available at the library in the Mathematikon)
  - Convex Optimization Theory, Athena Scientic, 2009 by D.P. Bertsekas, MIT,
Supplementary Chapter 6 on Convex Optimization Algorithms (2014) (in particular
chapter 6.3)
  - Convex Optimization: Algorithms and Complexity, S. Bubeck, Foundations and Trends in
Machine Learning, 2015 (in particular chapter 3.1)

Mirror Descent
: - Convex Optimization: Algorithms and Complexity, S. Bubeck, Foundations and Trends in
Machine Learning, 2015 (in particular, chapter 4)
  - Mirror descent and nonlinear projected subgradient methods for convex optimization, A.
Beck and M. Teboulle, Operation Research Letters, 2002

Proximal Gradient Methods
: - Amir Beck and Marc Teboulle, Gradient-Based Algorithms with Applications to Signal
Recovery Problems (Convex optimization in signal processing and communications, 2009)
(in particular sections 1.1 - 1.4)
  - Neal Parikh and Stephen Boyd, Proximal Algorithms (Foundations and Trends in
Optimization, 2014) (in particular chapters 1, 2, 4.2, 6, 7.1)

Accelerated Gradient Methods
: - Wright, Stephen J. "Optimization algorithms for data analysis." The Mathematics of Data
25 (2018): 49. (in particular section 6)

Smoothing for Nonsmooth Optimization
: - Amir Beck and Marc Teboulle, Smoothing and First Order methods: A Unied Framework
(SIAM Journal of Optimization, 2012)
  - Yuri Nesterov. Smooth minimization of non-smooth functions, (Mathematical
programming 103.1, 2005)

### Model Order Reduction
General recommendations
: - Model Order Reduction: Volume 1: System- and Data-Driven Methods and Algorithms, Berlin, Boston: De Gruyter, 2021. [https://doi.org/10.1515/9783110498967][morvol1]
  - Model Order Reduction: Volume 2: Snapshot-Based Methods and Algorithms, Berlin, Boston: De Gruyter, 2020. [https://doi.org/10.1515/9783110671490][morvol2]

Recommendations by topics
: Proper Orthogonal Decomposition (POD)
  : - [Lecture Notes of Stefan Volkwein][volkwein]
    - Chapter 2 of Model Order Reduction Volume 2
  
  Empirical Interpolation Method (EIM)
  : - Chapters 1.3.2 - 1.3.3 and chapters 5.4.2.1.1 - 5.4.2.1.3 of Model Order Reduction Volume 2
    - Grepl, Martin A., et al. "Efficient reduced-basis treatment of nonaffine and nonlinear partial differential equations." ESAIM: Mathematical Modelling and Numerical Analysis 41.3 (2007): 575-605.
    - Barrault, Maxime, et al. "An ‘empirical interpolation’ method: application to efficient reduced-basis discretization of partial differential equations." Comptes Rendus Mathematique 339.9 (2004): 667-672.
    - Chapter 5 of Hesthaven, Jan S., Gianluigi Rozza, and Benjamin Stamm. Certified reduced basis methods for parametrized partial differential equations. Vol. 590. Berlin: Springer, 2016.
    
  
  Reduced Basis Methods (RB)
  : - Chapter 4 of Model Order Reduction Volume 2
    - Chapter 3 of Hesthaven, Jan S., Gianluigi Rozza, and Benjamin Stamm. Certified reduced basis methods for parametrized partial differential equations. Vol. 590. Berlin: Springer, 2016.
    - Quarteroni, Alfio, Andrea Manzoni, and Federico Negri. Reduced basis methods for partial differential equations: an introduction. Vol. 92. Springer, 2015.
  
  Dynamic Mode Decomposition (DMD)
  : - Chapter 7 of Model Order Reduction Volume 2
    - Schmid, Peter J. "Dynamic mode decomposition of numerical and experimental data." Journal of fluid mechanics 656 (2010): 5-28.
  
  Derivative Extended POD (DEPOD)
  : - Schmidt, Andreas, et al. "Derivative-extended POD reduced-order modeling for parameter estimation." SIAM Journal on Scientific Computing 35.6 (2013)
    - Schmidt, Andreas. Direct Methods for PDE-Constrained Optimization Using Derivative-Extended POD Reduced-Order Models. Diss. 2014.
  
  Balanced Truncation
  : - Chapter 2 of Model Order Reduction Volume 1
  
  Rational Interpolation
  : - Chapter 3 of Model Order Reduction Volume 1
 
[kom]: #kick-off-meeting
[lit]: #literature
[ekaterina]: mailto:ekaterina(dot)kostina(at)iwr(dot)uni-heidelberg(dot)de
[ihno]: mailto:ihno(dot)schrot(at)uni-heidelberg(dot)de
[marta]: mailto:marta(dot)sauter(at)iwr(dot)uni-heidelberg(dot)de
[muesli]: https://muesli.mathi.uni-heidelberg.de/lecture/view/1692
[rubric]: https://www.bsu.edu/-/media/www/departmentalcontent/math/pdfs/cp%20rubric.pdf?la=en
[vpn]: https://www.urz.uni-heidelberg.de/en/service-catalogue/network/vpn-virtual-private-network

[morvol1]: https://doi.org/10.1515/9783110498967
[morvol2]: https://doi.org/10.1515/9783110671490
[volkwein]: https://www.math.uni-konstanz.de/numerik/personen/volkwein/teaching/2017WS-LQR-POD-Skript.pdf


