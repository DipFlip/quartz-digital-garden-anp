---
dg-publish: true
---

This is a collection of the gamma-ray imaging techniques developed by or in use by [[ANP (Appled Nuclear Physics)|ANP]]. 

- PSL (Point Source Localization) [paper](https://ieeexplore.ieee.org/document/8768340)
	- Can be run in discretized space (voxels)
	- Can be run in continuous space (faster than voxels!)
- APSL (Additative Point Source Localization)  [same as PSL paper](https://ieeexplore.ieee.org/document/8768340)
	- Is run in continuous space.
- GAPSL (Generalized Point Source Localization) [paper]( [paper](https://ieeexplore.ieee.org/document/8768340)
	- Takes APSL but instead of dirac-like point sources whose positions and intensities can be optimized GAPSL use Gaussian kernels. 
- MLEM (Maximum Likelihood Expectation Maximization)
	- Iterative algorithm that solves for the maximum likelihood estimate of intensity and background
	- Succeptive to overfitting in sparse and underdetermined scenarios
	- Typical MLEM fit shown below with increased source activity close to the measured path (image from [this paper](https://ieeexplore.ieee.org/document/8768340))
	- ![[Pasted image 20231002222251.png]]
- GPP (Gaussian Process Prior)
- Simultaneous NMF and Full Spectral Imaging with GPP
- MAP-EM (Maximum A Posteriori Expectation Maximization) [paper](https://www.nature.com/articles/s41598-021-99588-z.pdf)