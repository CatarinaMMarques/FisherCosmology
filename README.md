# FRIDDA

## Fisher foRecast code for combIned reDshift Drift and Alpha

Forecasting code, based on Fisher Matrix Analysis techiques, for the cosmological impact of redshift drift and fine-structure constant, $\alpha$, measurements as well as their combination. The final output of the code is the forecast of the measurements combination for the ArmazoNes high Dispersion Echelle Spectrograph (ANDES), instrument of the future Extremely Large Telescope (ELT) for two fiducial models - Bekenstein and Chevallier-Polarski-Linder (CPL) parametrization of dark energy. More details of the performed forecast and discussion of the results can be found at (article under revision).


### Code Structure

The structure of this repository is as follows:

- **Main:** Definition of the scaled Hubble parameter, fisher matrices, ellipses, figures of merit, correlation coefficients and uncertainties at 1-sigma.
- **RedshiftDrift:** Calculation of the spectroscopic velocities and respective uncertainties, identification of the redshift bins and uncertainties and also the priors. Definition of the fisher matrices considering redshift drift measurements only.
<br>
- **AlphaVariation:** Calculation of the $\alpha$ variation, identification of priors, redshift measurements and uncertainties. Definition of the fisher matrices for the $\alpha$ variation. 
<br>
- **RedshiftDriftAlphaVariation:** Definition of 7x7 matrices for the combination of redshift drift and $\alpha$ measurements.


### Contributors

The following people have contributed to FRIDDA: C. M. J. Marques, C. J. A. P. Martins and C. S. Alves.

The current code is based on the C. S. Alves code available at [fisher-forecast](https://github.com/Catarina-Alves/fisher-forecast).

A step by step guide that will tell you how to get the development environment up and running.


### Citation

If you use FRIDDA in your work please cite:

(article under revision - citation soon)
