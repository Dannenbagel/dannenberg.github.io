---
title: "Analysis Student Seminar Spring 2020"
layout: archive
permalink: /seminars/analysisstudentspring2020/
---

During this seminar we will investigate Liouville Quantum Gravity in some depth.  

This is a graduate student seminar, with talks given by graduate students participants.  We all attempt together to understand the topic being discussed.  Of course, people with any level of background are welcome, and everyone is especially encouraged to ask questions.

## Main Sources

These are the main articles we'll make use of this semester.  Other potentially useful sources are listed below the schedule.

  * Lawler, _Notes on Probability_ [Prob1](http://www.math.uchicago.edu/~lawler/probnotes.pdf)
  * Berestycki, _Introduction to the Gaussian Free Field and Liouville Quantum Gravity_ [LQG2](http://www.statslab.cam.ac.uk/~beresty/Articles/oxford4.pdf)
  * Le Gall, _Brownian Geometry_ [TBM2](https://link.springer.com/article/10.1007/s11537-019-1821-7)

## Schedule

All meetings are held on Wednesdays at 4pm in the Math Tower, Room 5-127.

Reading sections in parentheses are optional, and we'll likely exclude them unless we have spare time.

| Date   | Speaker   | Topic      | Reading Sections |
| ----- | -------------------- | ------------------------------------------------------------ | -------------- |
| 1/29/2020  | N/A    | Topic Proposals and Introduction | N/A |
| 2/5/2020   | Timothy Alland    | A Crash Course on Probability, Martingales | **Prob1** 1-5 |
| 2/12/2020  | Timothy Alland    | An Introduction to Martingales | **Prob1** 6-7 |
| 2/19/2020  | Matthew Dannenberg    | Brownian Motion, Brownian Bridges, Gaussian Random Variables | **Prob6** 2.2.1-2.2.2 |
| 2/26/2020  | Jack Burkart    | The Continuous Gaussian Free Field | **LQG2** 1.2-1.3,(1.4) |
| 3/4/2020   | N/A    | Markov and Conformal Properties of the GFF, Circle Regularization, Thick Points | **LQG2** 1.5-1.8 |
| 3/11/2020  | N/A    | Introduction to Liouville Quantum Gravity in the $L^2$ Phase | **LQG2** 2-2.2 |
| 3/18/2020  | N/A    | _Spring Break_ | N/A |
| 3/25/2020  | N/A    | Typical Points for the Liouville Measure, Random Surfaces and Conformal Structure | **LQG2** 2.3,2.5-2.7 |
| 4/1/2020   | N/A    | TBD | N/A |
| 4/8/2020   | N/A    | TBD | N/A |
| 4/15/2020  | N/A    | TBD | N/A |
| 4/22/2020  | N/A    | TBD | N/A |
| 4/29/2020  | N/A    | TBD | N/A |
| 5/6/2020   | N/A    | TBD | N/A |
| 5/13/2020  | N/A    | TBD | N/A |


## Potentially Useful Materials

A few of these resources we'll work through in detail.  The rest should be thought of as context for those interested or as reference documents containing proofs of certain results we'll use along the way.

This [course website](http://math.mit.edu/~sheffield/fall2017math177.html) from a 2017 MIT class taught by Scott Sheffield contains several really useful resources.

#### Probability

  * Lawler, _Notes on Probability_ [Prob1](http://www.math.uchicago.edu/~lawler/probnotes.pdf)
    * A crash course to terminology common in probability.  Particularly useful as a reference.
    * Some extra terminology to be aware of which is not used in Lawler:
      1. The **law** of a random variable is termed the **distribution** of the random variable in Lawler - both mean the same thing.  If $f: \Omega \to X$ is a random variable with $P$ the probability measure on $\Omega$, then the **law** of $f$ is the resulting pushforward measure on $X$.
      2. If $(\Omega_1, P_1)$ and $(\Omega_2, P_2)$ are probability spaces with $f: \Omega_1 \times \Omega_2 \to X$ (for $X$ a vector space), then the **marginal** or **marginal distribution** or **marginal law** of $f$ on $\Omega_1$ is the random variable $\int_{\Omega_2} f(x,y) dP_2(y)$.
  * Lawler, _Conformally Invariant Processes in the Plane_ [Prob2](http://users.ictp.it/~pub_off/lectures/lns017/Lawler/Lawler.pdf)
    * Chapter 2 is a useful reference for some of the basic properties of Brownian Motion, particularly conformal invariance.
  * `Uncertain Author`, _Stochastic Analyis, An Introduction_ [Prob3](http://math.tkk.fi/teaching/stokanal/lecture3.pdf)
    * The proof of the martingale convergence theorem and some useful other results are contained within.
  * Bell, _The Kolmogorov Extension Theorem_ [Prob4](http://individual.utoronto.ca/jordanbell/notes/kolmogorov.pdf)
    * This contains some nice review about $\sigma$-algebras and leads to the proof of the Kolmogorov Extension Theorem.
  * Berestycki, _Stochastic Calculus and Applications_ [Prob5](http://www.statslab.cam.ac.uk/~beresty/teach/sc3.pdf)
    * A thorough introduction to stochastic calculus.  Largely unneeded by us, it's still useful as a reference.
  * Taylor, _Random Fields_ [Prob6](http://statweb.stanford.edu/~jtaylo/courses/stats352/notes/random_fields.pdf)
    * This is included as a reference mainly for sections 2.2.1 and 2.2.2, which give a good self-contained definition of _Gaussian Random Variables_.
      * Extra terminology: A **centered Gaussian random variable** is a Gaussian random variable with mean 0.

#### Gaussian Free Fields

  * Sheffield, _Gaussian Free Fields for Mathematicians_ [GFF1](https://arxiv.org/abs/math/0312099)
    * A formal, functional-analytic description of Gaussian Free Fields.
  * Werner, _Topics on the two-dimensional Gaussian Free Field_ [GFF2](https://pdfs.semanticscholar.org/2607/b47d11a2b1758063795bb33348d9f963011d.pdf)
    * A mostly probabilistic description of the 2D Gaussian Free Field with some intuition from Brownian Motion.

#### Liouville Quantum Gravity

  * Gwynne, _Random Surfaces and Liouville Quantum Gravity_ [LQG1](https://arxiv.org/abs/1908.05573)
    * This is a survey article written to be readable to graduate students.  It's useful to skim as an explanation of a lot of the modern work on LQG.
  * Berestycki, _Introduction to the Gaussian Free Field and Liouville Quantum Gravity_ [LQG2](http://www.statslab.cam.ac.uk/~beresty/Articles/oxford4.pdf)
    * This is written to be a softer introduction to LQG, assuming only a background in probability.
  * Chern, _An Elementary Proof of the Existence of Isothermal Parameters on a Surface_ [LQG3](https://www.jstor.org/stable/2032933)
    * For any so curious, this paper proves the existence of isothermal coordinates using only the assumption that the Riemannian metric is Holder continuous.
  * Duplantier, Sheffield, _Liouville Quantum Gravity and KPZ_ [LQG4](https://arxiv.org/abs/0808.1560)
    * A very detailed, but somewhat more difficult to parse explanation of LQG.
  * Rhodes, Vargas, _Gaussian Multiplicative Chaos and Applications: A Review_ [LQG5](https://arxiv.org/abs/1305.6221)
    * While on its face this topic does not seem clearly related to LQG, multiplicative chaos is in fact the general case, with LQG being an example of multiplicative chaos applied to the GFF.  We won't use this in the seminar, but it may be of interest.

#### The Brownian Map

  * Le Gall, Miermont, _Scaling Limits of Random Trees and Planar Maps_ [TBM1](https://arxiv.org/abs/1101.4856)
    * This article goes into exhaustive detail into each of the constituent types of discrete and continuous objects which are used in a thorough construction of the Brownian Map.  It also features some very descriptive pictures.
  * Le Gall, _Brownian Geometry_ [TBM2](https://link.springer.com/article/10.1007/s11537-019-1821-7)
    * A more concise description of the material leading to the Brownian Map, with a bit less detail in the proofs but more focus on intuition.
  

