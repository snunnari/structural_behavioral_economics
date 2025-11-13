# Structural Behavioral Economics with Python and Julia

### Authors

- Massimiliano Pozzi (University of Zurich)
- Salvatore Nunnari (Bocconi University, https://snunnari.github.io, salvatore.nunnari@unibocconi.it)

### About

This repository contains Python and Julia notebooks to replicate the structural estimates of a set of papers in the field of Behavioral Economics. Following DellaVigna (*Handbook of Behavioral Economics*, 2018), we define structural as *"the estimation of a model on data that recovers estimates (and confidence intervals) for some key behavioral parameters"*. [Python](https://www.python.org) and [Julia](https://julialang.org) are two programming languages that offer some advantages compared to others often used by economists, namely, they are free and open source (which promotes replicability, since anybody with a computer can set up the environment and run the code) and are easy to read (and to write in!). While the main disadvantage of Python (with respect to, e.g., Matlab) is its speed, Julia is blazingly fast. We hope this resource can help other researchers and ease the transition from Stata, R and Matlab to Python and Julia.

### How Do I Navigate This Repository?

This repository contains one folder for each paper whose structural estimates we replicate. Each folder contains five sub-folders named: paper, original_replication_files, code, input, and output. The sub-folder "paper" contains .pdf files for the paper and its appendices. The sub-folder "original_replication_files" contains the replication datasets and codes downloaded from the journal's website. The sub-folder "code" contains the notebooks we created to replicate the paper's structural estimates with Python and Julia; the Python notebook has extension .ipynb (and can be opened with [Jupyter](https://jupyter.org)) while the Julia notebook has extension .jl (and can be opened with [Neptune](https://github.com/compleathorseplayer/Neptune.jl) and [Pluto](https://github.com/fonsp/Pluto.jl)). The sub-folder "input" contains all the data imported in the notebooks to generate the estimates. The sub-folder "output" contains .csv files with the estimation results obtained running the notebooks.

### What Papers Does Your Code Replicate?

This repository contains the notebooks to replicate the main structural estimates in the following papers:

- Ned Augenblick and Matthew Rabin, 2019, "An Experiment on Time Preference and Misprediction in Unpleasant Tasks", *Review of Economic Studies*, 86(3): 941&ndash;975
	- Estimation Method: Maximum Likelihood
	- Source of Heterogeneity: Implementation Errors
- Adrian Bruhin, Ernst Fehr, and Daniel Schunk, 2019, "The Many Faces of Human Sociality: Uncovering the Distribution and Stability of Social Preferences", *Journal of the European Economic Association*, 17(4): 1025&ndash;1069
	- Estimation Method: Maximum Likelihood, SEAM/EM-Algorithm
	- Source of Heterogeneity: Random Utility, Finite Mixture
- Stefano DellaVigna, John A. List, Ulrike Malmendier, and Gautam Rao, 2017, "Voting To Tell Others", *Review of Economic Studies*, 84(1): 143&ndash;181
	- Estimation Method: Simulated Method of Moments
	- Source of Heterogeneity: Random Parameters
- Stefano DellaVigna and Devin Pope, 2018, "What Motivates Effort? Evidence and Expert Forecasts", *Review of Economic Studies*, 85(2): 1029&ndash;1069
	- Estimation Method: Generalized Method of Moments (+ Boostrapped SEs), Non-Linear-Least-Squares
	- Source of Heterogeneity: No Noise in GMM, Random Parameters in NLLS

We chose these papers to replicate because (a) they were recently published in general interest journals and, as such, they constitute the state-of-the-art in structural behavioral economics, (b) the replication files are available on the journal's website, and (c) they allow us to explore a wide array of different estimation methods and sources of heterogeneity (the two building blocks of a structural model, as discussed in Sections 4.1 and 4.2 of DellaVigna 2018 and detailed in the list above).

### Where Can I Learn More About Python?

- [Learn Python in Y Minutes](https://learnxinyminutes.com/docs/python/)
- [Quantitative Economics with Python](https://quantecon.org/python-lectures/)
- [Python for Econometrics, Statistics and Numerical Analysis](https://www.kevinsheppard.com/teaching/python/notes/) (Kevin Sheppard)
- [PyEcon](https://pyecon.org)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Coding for Economists](https://aeturrell.github.io/coding-for-economists) (Arthur Turrell)

### Where Can I Learn More About Julia?

- [Learn Julia in Y Minutes](https://learnxinyminutes.com/docs/julia/)
- [Quantitative Economics with Julia](https://julia.quantecon.org/intro.html)
- [The Fast Track To Julia](https://juliadocs.github.io/Julia-Cheat-Sheet/)
- [Computational Economics for PhDs](https://floswald.github.io/NumericalMethods/) (Florian Oswald)

### Where Can I Learn More About Structural Models?

 - DellaVigna, Stefano, 2018, "Structural Behavioral Economics," *Handbook of Behavioral Economics Vol. 1*, North-Holland, 613&ndash;723
 - Holmes, Thomas and Holger Sieg, 2015, "Structural Estimation in Urban Economics," *Handbook of Regional and Urban Economics Vol. 5*, Elsevier, 69-114
 - Keane, Michael, Petra Todd, and Kenneth Wolpin, 2011, "The Structural Estimation of Behavioral Models: Discrete Choice Dynamic Programming Methods and Applications," *Handbook of Labor Economics Vol. 4*, Elsevier, 331&ndash;461
 - Low, Hamish and Costas Meghir, 2017, "The Use of Structural Models in Econometrics," *Journal of Economic Perspectives*, 31(2): 33&ndash;58
 - McLachlan, Geoffrey, Sharon Lee, and Suren Rathnayake, 2019, "Finite Mixture Models," *Annual Review of Statistics and Its Application*, 6: 355&ndash;378
 - Reiss, Peter and Frank Wolak, 2007, "Structural Econometric Modeling: Rationales and Examples from Industrial Organization," *Handbook of Econometrics*, 6: 4277&ndash;4415
 - Todd, Petra and Kenneth Wolpin, 2010, "Structural Estimation and Policy Evaluation in Developing Countries," *Annual Review of Economics*, 2:21&ndash;50
