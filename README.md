# lenstronomy-metals-notebooks
## A compliment Jupyter notebook to [Metha et al. 2024](https://arxiv.org/abs/2403.08175)

Hello researcher! I'm Benji Metha, one of the developers for Lenstronomy's tracer module. This Notebook contains a tutorial for using lenstronomy on light-weighted galaxy data, such as metallicity maps. 

To make it work, you need three things:

* Observations of the light distribution of the system (It's also fine to use a bright emission line, such as Hα).
* Observations of the 2D metallicity distribution of the system (or another light-weighted property of the galaxy, such as velocity or stellar age), with uncertainties at all points.
* An estimate of the point spread function of the telescope.

This approach offers two benefits over a traditional approach: Firstly, it corrects for the effects of PSF smearing. Secondly, it allows asymmetric models to be fit to metallicity profiles that do not appear to be radially symmetric.

For more details on the `lenstronomy` package and for citation purposes, you can find the two `lenstronomy` introductory papers here:  
<https://ui.adsabs.harvard.edu/abs/2018PDU....22..189B/abstract>  
<https://ui.adsabs.harvard.edu/abs/2021JOSS....6.3283B/abstract>

To install `lenstronomy`, which contains the tracer module that this tutorial covers, follow <https://github.com/lenstronomy>.

If you have any questions, please reach out! I am friendly and approachable!  
methab (at) student.unimelb.edu.au   
:) 
