# FRIDDA
### Fisher foRecast code for combIned reDshift Drift and Alpha

Forecasting code, based on Fisher Matrix Analysis techniques, for the cosmological impact of redshift drift and fine-structure constant, $\alpha$, measurements as well as their combination. The final output of the code is the forecast of the measurements combination for the ArmazoNes high Dispersion Echelle Spectrograph (ANDES), instrument of the future Extremely Large Telescope (ELT) for two fiducial models - Bekenstein and Chevallier-Polarski-Linder (CPL) parametrization of dark energy. More details of the performed forecast and discussion of the results can be found at Marques, C.M.J., Martins, C.J.A.P.,  Alves, C.S., Fundamental cosmology from ANDES precision spectroscopy, Monthly Notices of the Royal Astronomical Society, Volume 522, Issue 4, July 2023, Pages 5973–5979, https://doi.org/10.1093/mnras/stad1359.


## Code Structure

The structure of this repository is as follows:

- **Main:** Definition of the scaled Hubble parameter, fisher matrices, ellipses, figures of merit, correlation coefficients and uncertainties at 1-sigma.
- **RedshiftDrift:** Calculation of the spectroscopic velocities and respective uncertainties, identification of the redshift bins and uncertainties and also the priors. Definition of the fisher matrices considering redshift drift measurements only.
- **AlphaVariation:** Calculation of the $\alpha$ variation, identification of priors, redshift measurements and uncertainties. Definition of the fisher matrices for the $\alpha$ variation only. 
- **RedshiftDriftAlphaVariation:** Matrices definition for the combination of redshift drift and $\alpha$ measurements.


## Contributors

The following people have contributed to FRIDDA: C. M. J. Marques, C. J. A. P. Martins and C. S. Alves.

The current code is based on the C. S. Alves code available at [fisher-forecast](https://github.com/Catarina-Alves/fisher-forecast).


## Citation

If you use FRIDDA in your work please cite:

Marques, C.M.J., Martins, C.J.A.P.,  Alves, C.S., Fundamental cosmology from ANDES precision spectroscopy, Monthly Notices of the Royal Astronomical Society, Volume 522, Issue 4, July 2023, Pages 5973–5979, https://doi.org/10.1093/mnras/stad1359
