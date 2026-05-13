[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# GLOBE
Code for our AAAI 2021 paper titled [Discovering Fully Oriented Causal Networks](https://ojs.aaai.org/index.php/AAAI/article/view/17085)

> Tldr: We discover fully oriented causal graphs in a score-based DAG search, using the Algorithmic Markov Condition.


Use **`main.py`** to see an example of how the code works.


----------------------------------------------------------
REQUIREMENTS:
----------------------------------------------------------
- Python version: 3.7 or better
- Packages:
	* scikit-learn
	* numpy
	* mpmath
	* matplotlib
	* cdt (causal discovery toolbox)
    * rpy2 (to run Rcode of earth regression spline package)  

- R Version: 3.6 or better
- R packages:
	* SID: 	 https://www.rdocumentation.org/packages/SID/versions/1.0
	* pcalg: https://www.rdocumentation.org/packages/pcalg/versions/2.6-8
	* kpcalg/RCIT:  https://github.com/Diviyan-Kalainathan/RCIT
	* spresebn: https://www.rdocumentation.org/packages/sparsebn/versions/0.1.0
	* bnlearn: https://www.rdocumentation.org/packages/bnlearn/versions/4.5
    * earth: https://cran.r-project.org/package=earth

## Notes
- This version of GLOBE has been cleaned and commented for the ease of use. The implementation can be further optimized but is not in my immediete plans.
- If you would like to reproduce the results of the experiments stated in the publication, you can find the data and the (automated) version of GLOBE on this link: https://www.dropbox.com/sh/iuy4cv7uzn54m6u/AADH5C7wdC-jQG73RD4rZOXAa?dl=0
- There are two files that mainly map to the "Algorithm" section of the publication: SkeletonHandler.sh (Contains the edge ranking phase) and DAG.py (contains Forward and Backward Search phases)
- For scoring functions mentioned in the published work, refer to globe.py
- This code is not optimized for performance and may contain some unused variables within. Although, I have done my best to resolve the latter.	


Code Last Modified: 22nd August 2022

## Contact
For errors and corrections, please reach out via https://sites.google.com/view/mian.

