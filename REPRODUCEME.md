APOGEE / Hipparcos
==================

1. Cross-match APOGEE (v603) and Hipparcos (2007) catalogs. This gives you `data/APOGEE-allStar-v603-Hipparcos.fits.gz`

2. `cd` to the `data/` 

3. Run `get_apogee_hipparcos_spectra.py` to download the APOGEE Hipparcos spectra.

4. Run `get_apogee_cluster_spectra.py` to download (some of) the APOGEE cluster spectra. 

5. Run `get_apogee_ness_cluster_spectra.py` to download the APOGEE cluster spectra used in Ness et al. (2015).

6. `cd ../`

7. `python apogee_model.py` to run a model (e.g., `hipparcos_clusters.yaml`)

