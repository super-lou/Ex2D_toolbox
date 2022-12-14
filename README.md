# Ex2D toolbox [<img src="resources/LogoExplore2.png" align="right" width=160 alt=""/>](https://professionnels.ofb.fr/fr/node/1244)

<!-- badges: start -->
[![Lifecycle: maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://lifecycle.r-lib.org/articles/stages.html)
![](https://img.shields.io/github/last-commit/super-lou/Ex2D_toolbox)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md) 
<!-- badges: end -->

**Ex2D toolbox** is a R toolbox based on [EXstat](https://github.com/super-lou/EXstat) and [CARD](https://github.com/super-lou/CARD) packages which provide a simple way of interacting with all these codes to carry out diagnostic of hydrological models used in [Explore2](https://professionnels.ofb.fr/fr/node/1244).

This project was carried out for National Research Institute for Agriculture, Food and the Environment (Institut National de Recherche pour l’Agriculture, l’Alimentation et l’Environnement, [INRAE](https://agriculture.gouv.fr/inrae-linstitut-national-de-recherche-pour-lagriculture-lalimentation-et-lenvironnement) in french).


## Installation
For latest development version
``` 
git clone https://github.com/super-lou/Ex2D_toolbox.git
```


## Help
You can find different help script in this the [help](https://github.com/super-lou/Ex2D_toolbox/tree/main/help) directory.

### DRIAS NetCDF exportation
In the [help](https://github.com/super-lou/Ex2D_toolbox/tree/main/help) directory, you will have the [DRIAS_export](https://github.com/super-lou/Ex2D_toolbox/tree/main/help/DRIAS_export) directory which includes 2 subdirectories, one for [1D data exportation](https://github.com/super-lou/Ex2D_toolbox/tree/main/help/DRIAS_export/DRIAS_export_1D) and the other for [2D data exportation](https://github.com/super-lou/Ex2D_toolbox/tree/main/help/DRIAS_export/DRIAS_export_2D).

You can make your choice between [1D](https://github.com/super-lou/Ex2D_toolbox/tree/main/help/DRIAS_export/DRIAS_export_1D) and [2D](https://github.com/super-lou/Ex2D_toolbox/tree/main/help/DRIAS_export/DRIAS_export_2D) DRIAS NetCDF exportation and find a README in each subdirectory.

### Formatted Rdata exportation
In [Rdata_export](https://github.com/super-lou/Ex2D_toolbox/tree/main/help/Rdata_export), there is an example of what formatted data for Explore2 looks like.


## Main execution
In the principal directory of this toolbox you will find the [main.R](https://github.com/super-lou/Ex2D_toolbox/tree/main/main.R) script which is dedicated to fast global execution of the Explore2 diagnostic by using [MKstat](https://github.com/super-lou/MKstat), [ashes](https://github.com/super-lou/ashes) and [dataSheep](https://github.com/super-lou/dataSheep) R package.

*in construction*


## FAQ
*I have a question.*

-   **Solution**: Search existing issue list and if no one has a similar question create a new issue.

*I found a bug.*

-   **Good Solution**: Search existing issue list and if no one has reported it create a new issue.
-   **Better Solution**: Along with issue submission provide a minimal reproducible example of the bug.
-   **Best Solution**: Fix the issue and submit a pull request. This is the fastest way to get a bug fixed.


## Code of Conduct
Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
