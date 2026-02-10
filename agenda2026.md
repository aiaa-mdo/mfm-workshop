## 3rd AIAA Workshop on Multifidelity Methods for Design and Uncertainty Quantification

June 7, 2026 

San Diego, CA, USA

In conjunction with AIAA Aviation Forum 2026

[Registration is open now!](https://aiaa.org/courses/aiaa-workshop-for-multifidelity-modeling-in-support-of-design-and-uncertainty-quantification/)

### Tentative Agenda

| Time         |                                                                                                                                     | Speaker          |
|:-------------|:------------------------------------------------------------------------------------------------------------------------------------|:-----------------|
| 7am          | Check-in opens                                                                                                                      |                  |
| 8am          | Lecture 1: CFD Industry Perspectives                                                                                                | Ray Humble       |
| 8:30am       | Lecture 2: AI-driven multifidelity multidisciplinary design optimization (MF-MDO)                                                   | Ahmed Bayoumy    |
| 9:30am       | Break                                                                                                                               |                  |
| 10am         | Lecture 3: Multi-Fidelity Uncertainty Quantification                                                                                | Markus Rumpfkeil |
| 11am         | Lunch break                                                                                                                         |                  |
| 1pm          | Lecture 4: Accelerating Uncertainty Quantification with Multifidelity Statistical Estimators: From Theory to Practice with PyApprox | John Jakeman     |
| 2pm          | Lecture 5: Multifidelity Gaussian Process Modeling                                                                                  | Elizabeth Qian   |
| 3pm          | Break                                                                                                                               |                  |
| 4pm          | Panel                                                                                                                               | All speakers     |
| 5pm          | Workshop concludes                                                                                                                  |                  |
  
### Talk abstracts and speaker bios

#### Lecture 1: CFD Industry Perspectives
Across industry, the landscape is shifting from traditional hardware‑centric testing toward
a digital‑first paradigm. Modern development programs are increasingly relying on modeling and
simulation to replace, or significantly reduce, expensive physical testing, driven by initiatives such
as Simulation‑Based Verification (SBV) and Certification‑by‑Analysis (CbA). To meet aggressive
schedule and cost constraints, organizations are embracing multi-fidelity modeling strategies:
relatively inexpensive, low‑fidelity models are used for rapid design space exploration, while a
targeted set of high‑fidelity simulations anchors accuracy, and uncertainty quantification
methodologies facilitate risk-informed decision making. This talk will synthesize key trends, and
offer a broad perspective of today’s evolving CFD ecosystem and its role in multi-fidelity design
and uncertainty quantification workflows.

_Raymond A. Humble, Lockheed Martin Aeronautics_

Dr. Humble is the CFD Manager at Lockheed Martin Aeronautics. He has almost 20 years’
experience in aerospace engineering spanning hypersonic, rarefied-gas, supersonic, and subsonic
regimes. Prior to Lockheed Martin, he served as Sr. Principal Engineer at Raytheon Missiles &
Defense, directing program and IRAD efforts in hypersonic aerothermodynamics. Prior to that, he
worked at GE Aerospace’s Advanced Technology Organization, where he conducted aerodynamic
design and directed technology maturation test campaigns. He was a Postdoctoral Research
Associate at Texas A&M University, where he supported several NASA/AFOSR aeroscience
programs. He holds a Ph.D. from Delft University, where he advanced the application of
tomographic particle image velocimetry to study shock-wave/turbulent-boundary-layer
interactions. He has authored over 40 peer-reviewed journal articles, conference papers, and
company trade secret disclosures.

#### Lecture 2: AI-driven Multifidelity Multidisciplinary Design Optimization (MF-MDO)
The integration of artificial intelligence (AI) tools into multidisciplinary design optimization (MDO) methods aims at accelerating the MDO process and ensuring that engineering systems will perform as predicted. Progress in this area involves combining physics-based and data-driven models to develop effective multi-fidelity machine learning (MFML) solutions. However, challenges inherent to the complexity of engineering systems may impact the usefulness of MFML solutions in the MDO process. In this tutorial, we highlight the significance of employing uncertainty-aware AI models in multi-fidelity model management to enhance the robustness of the optimization process and model selection in MF-MDO. Attendees will gain practical insights into current industry practices, integration strategies, open-source tools, and emerging trends in the application of AI to MF-MDO.

_Ahmed Bayoumy, Siemens Digital Industries Software_

Dr. Bayoumy is an optimization specialist and advanced numerical methods engineer at Siemens Digital Industries Software. He is responsible for developing innovative strategies and software solutions related to multidisciplinary design optimization (MDO) of complex engineering systems. Before joining Siemens, Dr. Bayoumy was first a PhD student and then a postdoctoral researcher at the Systems Optimization Laboratory in the Department of Mechanical Engineering of McGill University. His research was co-funded by the Canadian National Science and Engineering Research Council and Siemens Energy, enabling him to implement and apply his relative adequacy framework for multimodel management to aero-derivative gas turbine MDO problems.

#### Lecture 3: Multi-Fidelity Uncertainty Quantification 
In this tutorial, an introduction to uncertainty quantification (UQ) is given. UQ consists of three phases: 1. characterization of the uncertainties in the input parameters; 2. uncertainty propagation in which the input variabilities are propagated through the model; 3. calculation of the statistical properties and confidence bounds of the output quantities of interest. It will be briefly discussed which UQ methods are useful when the input uncertainties cannot be characterized well but the emphasis in this tutorial will be on efficient uncertainty propagation techniques. To this end, the construction of multi-fidelity sparse polynomial chaos expansion (SPCE), kriging as well as a combination of the two surrogate approaches into a multi-fidelity SPCE-Kriging model will be discussed. Analytical benchmark problems are used to demonstrate the promise of these approaches to inexpensively propagate uncertainties through a computational model. Overall, multi-fidelity models yield more accurate estimates of statistics of interest compared to using high-fidelity data alone at the same computational cost or conversely a similar accuracy can be achieved at a cheaper computational cost. In addition, an optimization under uncertainty (OUU) test case is considered as a practical application for efficient UQ propagation. In particular, a gradient-based transonic airfoil lift-constrained robust drag minimization example is demonstrated and it is shown that a first-order moment method and a kriging approach can both lead to successful and computationally manageable robust optimizations.

_Dr. Markus Rumpfkeil, University of Dayton_

Markus Peer Rumpfkeil is a Professor at the University of Dayton (UD) Department of Mechanical and Aerospace Engineering and the Aerospace Director. Before joining UD, Markus was a Post-doctoral Research Assistant at the University of Wyoming working with Professor Dimitri Mavriplis on efficient Hessian calculations and Uncertainty Analysis. He earned his Ph.D. from the University of Toronto Institute for Aerospace Studies (UTIAS) under the supervision of Professor David Zingg. He also obtained a Diplom (a combined B.Sc. and M.Sc.) in Physics from the Humboldt University of Berlin, Germany, with a minor in Mathematics. He wrote his Master’s thesis at the Max-Planck Institute for Gravitational Physics in Potsdam-Golm, Germany. He is an Associate Fellow of the American Institute of Aeronautics and Astronautics (AIAA) and a former chair of the AIAA Technical Committee Non-Deterministic Approaches. He was a member of the Technical Team of NATO AVT-354 on “Multi-Fidelity Methods for Military Vehicle Design” which won the 2024 AVT Panel Excellence Award. His research interest is the broad area of uncertainty quantification and design optimization applied to computational fluid dynamics problems in which he has published more than one hundred peer reviewed journal and conference papers and has advised more than two dozen graduate students.

#### Lecture 4: Accelerating Uncertainty Quantification with Multifidelity Statistical Estimators: From Theory to Practice with PyApprox
Simulating complex phenomena for model-aided decision making---such as safety certification of engineered systems or the design of new systems---often requires computationally expensive high-fidelity models. Yet even as these models become increasingly predictive, quantities of interest needed for decisions remain subject to substantial uncertainty that must be quantified, for example through statistics such as the mean and standard deviation of model predictions. Standard Monte Carlo estimation using only high-fidelity simulations provides unbiased estimates, but is often impractical because limited simulation budgets lead to large estimator variance and, consequently, large mean-squared error (MSE). In contrast, surrogate-based approaches (e.g., polynomial chaos expansions, sparse grids, and Gaussian-process models) can reduce computational cost substantially, but introduce bias and approximation error that can be difficult to control, especially in high-dimensional settings.

This tutorial presents multifidelity statistical estimation methods for uncertainty quantification that combine the strengths of both approaches. The central idea is to preserve unbiasedness by using a limited number of high-fidelity evaluations while leveraging a large number of inexpensive low-fidelity evaluations---derived from coarser discretizations, simplified physics, or surrogate models---to more thoroughly explore the uncertainty space and reduce estimator variance and MSE. We cover the end-to-end workflow: designing pilot studies, estimating multifidelity covariances, allocating samples optimally across fidelities, and constructing practical estimators once all simulations are collected. We also discuss common pitfalls, including sensitivity to inaccurate pilot estimates, and present strategies to mitigate their impact. The tutorial will be interactive, with hands-on code demonstrations using PyApprox throughout, so participants leave with a working understanding of how to apply these methods to their own problems of interest. Emphasis is placed on the fact that even low-fidelity models that do not enforce key high-fidelity properties can still be exploited to produce unbiased statistics at a fraction of the cost of high-fidelity Monte Carlo.

_John Davis Jakeman, Sandia National Laboratory_

Dr. Jakeman is a Principal Member of Technical Staff at Sandia National Laboratories. He develops supervised machine learning methods for modeling physical processes and enabling credible, data-informed decision making under uncertainty, with an emphasis on prediction and decision making using data and models of varying credibility and cost. He is the founding developer of PyApprox, an open-source Python toolbox for machine learning, uncertainty quantification, parameter estimation, and design of experiments, supported by extensive documentation, tutorials, and examples. His research contributions include multifidelity information fusion; surrogate modeling (e.g., Gaussian processes and polynomial chaos expansions); operator learning; optimal experimental design; probabilistic inverse problems (including Bayesian and push-forward inference); and emerging approaches at the intersection of uncertainty quantification and generative AI. He has applied these methods to high-consequence problems in engineering (acoustics, additive manufacturing, aerospace design), national-security-relevant Earth science applications (including ice-sheet and sea-ice evolution), and plasma physics (high-density fusion). He received his Ph.D. in Mathematics from the Australian National University in 2011.

#### Lecture 5: Multifidelity Gaussian Process Modeling 
Gaussian processes provide a powerful and flexible framework for modeling nonlinear functional relationships with uncertainty estimates. Gaussian process regression, also known as kriging, is a class of methods that fit Gaussian processes to data, yielding efficient surrogate models that can be used as emulators for expensive high-fidelity models, enabling many-query analyses in multidisciplinary design, optimization, and uncertainty quantification. However, when high-fidelity training data are limited, the trained Gaussian process models can have unacceptably high uncertainties or errors that make them unreliable for use in these engineering decision-making contexts. To address this challenge, multifidelity Gaussian process modeling strategies leverage both limited high-fidelity data and more abundant lower-fidelity data in training to learn more accurate Gaussian process models from limited high-fidelity data. This tutorial will provide an introduction to Gaussian processes and Gaussian process regression, followed by a high-level overview of the state of the art in multifidelity Gaussian process modeling. 

_Elizabeth Qian, Georgia Institute of Technology_

Dr. Qian is an Assistant Professor at Georgia Tech, jointly appointed in the School of Aerospace Engineering and the School of Computational Science and Engineering. Her interdisciplinary research develops new computational methods to enable engineering design and decision-making for complex systems. Her specialties are in developing efficient surrogate models through model reduction and scientific machine learning, and in developing multifidelity approaches to accelerate expensive computations in uncertainty quantification, optimization, and control. Previously, she was a von Karman Instructor at Caltech in the Department of Computing and Mathematical Sciences. She earned her PhD, SM, and SB degrees from the MIT Department of Aeronautics & Astronautics. Highlights of her awards and honors include the NSF CAREER and Air Force Office of Scientific Research Young Investigator Program awards, as well as a Caltech-wide teaching award from the undergraduate student body, the Fannie and John Hertz Foundation Fellowship, and a U.S. Fulbright Student grant. She currently holds a visiting faculty appointment as a Hans Fischer Fellow at the Technical University of Munich.

