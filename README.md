# JWST PSF library supplemental code

Tutorial code to use the PSF library for JWST/NIRCam coronagraphy presented in Ferrer-Chavez et al. (2026). 

The observations that constitute the PSF library can be found in the associated Zenodo repository (https://doi.org/10.5281/zenodo.24119856), specifically under nanreplaced_masked.zip.

With those observations, the notebook in this repository shows how to use them (optionally in addition to other available reference PSF observations) to reduce a science target with spaceKLIP, all the way from the current state of the data products (right after JWST pipeline stages 1 and 2, and custom bad pixel cleaning) to PSF-subtracted data products with KLIP via pyKLIP.

Below are some important versions for specific software packages; for a complete list, see environment.yml file in the Zenodo repository.
- jwst: 1.20.2
- mocapy: 0.1.dev77+g43e7c9e
- numpy: 1.26.4
- pandas: 2.2.2 
- photutils: 2.3.0 
- poppy: 1.1.1
- pyklip: 2.9.1
- scipy: 1.16.3 
- spaceklip: 2.2.1.dev15+gf97eb19 
- stpsf: 2.1.1.dev65 
- webbpsf-ext: 2.0.1 
