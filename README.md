# Saturn-Atmosphere-NIRCam
Supplemental material for Fletcher et al. (2026) - NIRCam observations of Saturn's atmosphere and auroras.

**L.N. Fletcher, O.R.T. King, M. Garcia-Marin, S.C.A. Toogood, J.D. Nichols, A.A. Simon, M.H. Wong, M.T. Roman, C. Britt, M. Tiscareno, S.N. Milam, H.B. Hammel (2026), Saturn's Atmosphere and Auroras from JWST/NIRCam, submitted to JGR:Planets**

* **Imaging Observations:**  JWST observational data can be downloaded from the MAST archive for [programmes 1247](https://dx.doi.org/10.17909/jnfs-f677) and [9219](https://dx.doi.org/10.17909/48fp-9a16), processed with the JWST Calibration pipeline and PlanetMapper tools, to produce the mapped data in FITS format, but we provide our processed images as .png files in the `images` subdirectory, subdivided by filter and time.  These observations were used in Fig. 1 and Fig. 2,  polar projected in Fig. 6-9, and cylindrically projected in Fig. 11.  Hubble observations can be downloaded directly from the [OPAL archive](https://archive.stsci.edu/prepds/opal/) and were polar-projected in Fig. 10.

*  **Transmission Calculations:** The vertical sensitivity of the NIRCam filters was estimated by calculating the two-way transmission of photons travelling through Saturn's aerosol-free atmosphere in the nadir view.  Figure 3 was based on transmission and optical depth calculations on a wavelength-pressure grid - these are provided as .h5 files in the `transmission` subdirectory, along with some supporting PDF images.

*  **Zonal Means:** Figs. 4 & 5 display zonally-averaged properties of Saturn's atmosphere, extracted from the imaging data.  This includes the zonal-mean brightness, the poleward brightness gradient, the fitted nadir-brightness and Minnaert-k parameters for limb brightening/darkening, and their poleward gradients.  We provide all of these on a latitude grid as .csv files for each filter, along with an estimate of the quality of the zonal fit.

*  **Auroras:** Figs. 12 & 13 display auroral features as a function of latitude (degrees from the pole) and altitude, selecting representative frames from the time series.  The `auroras` subdirectory contains the images (as PDF files and .h5 files) for each frame, separated by wavelength.
