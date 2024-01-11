
# alineR: An R package for feature-weighted linguistic distances

The alineR R package enables calculation of quantitative phonetic distance measurments. It uses Grzegorz Kondrak's _aline_ algorithm (written in C) to generate a phonetic feature-based word similarity score. The alineR package provides convenience functions for analyzing vectors of words using default and user-specified feature weights. Advanced functions enable optimization of feature weights for a given dataset using a neural network. The package is described in "alineR: an R Package for Optimizing Feature-Weighted Alignments and Linguistic Distances" in The R Journal (2017) <http://doi.org/10.32614/RJ-2017-005>

Version: 2.0  
Published: 9 Jan 2024  
Authors: Sean S. Downey, Guowei Sun, Peter Norquest  
Maintainer: Ethan Kopf  
License:	GPL-3  
URL: https://github.com/downey205/alineR   

Correspondences: Sean Downey (<downey.205@osu.edu>)

# History

The first version of alineR was developed and published on CRAN in 2015 with funding provided by the National Science Foundation. Along with the R package, we published a paper that illustrated its use. After several years, evolving code standards and security protocols eventually resulted in the package being removed from CRAN. Archival versions can be found here: https://cran.r-project.org/package=alineR. Sean Downey, Guowei Sun, and Peter Norquest collaborated on this initial public release of alineR.

In 2023, Ethan Kopf joined the project and revised the code and R package to work with updated versions of R. This time, we are making this new version of alineR available on GitHub.

# Installation

Use these commands to install alineR_2.0:

>install.packages("remotes")  
>remotes::install_github("downey205/alineR")

# Disclaimer
The software is provided with no warranty expressed or implied. Please use at your own risk.

# References

If you use alineR please cite the following paper:


> @article{RJ-2017-005,  
>  author = {Sean S. Downey and Guowei Sun and Peter Norquest},  
>  title = {{alineR: an R Package for Optimizing Feature-Weighted
>          Alignments and Linguistic Distances}},  
>  year = {2017},  
>  journal = {{The R Journal}},  
>  doi = {10.32614/RJ-2017-005},  
>  url = {https://doi.org/10.32614/RJ-2017-005},  
>  pages = {138--152},  
>  volume = {9},  
>  number = {1} 
>}

Here is Grzegorz Kondrak's original publication documenting the aline algorithm. 

>@inproceedings{kondrak2000new,  
>  title={A new algorithm for the alignment of phonetic sequences},  
>  author={Kondrak, Grzegorz},  
>  booktitle={1st Meeting of the North American Chapter of the Association for Computational Linguistics},  
>  year={2000} 
>}

Other papers that use alineR by that have been published by our research group include the following:

>@article{downey2008computational,  
>  title={Computational feature-sensitive reconstruction of language relationships: Developing the ALINE distance for comparative historical linguistic reconstruction},  
>  author={Downey, Sean S and Hallmark, Brian and Cox, Murray P and Norquest, Peter and Lansing, J Stephen},  
>  journal={Journal of Quantitative Linguistics},  
>  volume={15},  
>  number={4},  
>  pages={340--369},  
>  year={2008},  
>  publisher={Taylor \& Francis}
>}

>@article{lansing2022deep,  
>  title={Deep ancestry of collapsing networks of nomadic hunter--gatherers in Borneo},  
>  author={Lansing, J Stephen and Jacobs, Guy S and Downey, Sean S and Norquest, Peter K and Cox, Murray P and Kuhn, Steven L and Miller, John H and Malik, Safarina G and Sudoyo, Herawati and Kusuma, Pradiptajati},  
>  journal={Evolutionary Human Sciences},  
>  volume={4},  
>  pages={e9},  
>  year={2022},  
>  publisher={Cambridge University Press} 
>}


