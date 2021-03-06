# Parity-Even-4PCF

This contains the analysis code used in Philcox et al. (2021b, [arXiv](https://arxiv.org/abs/2108.01670)) to constrain non-Gaussianity in the isotropic connected 4-point correlation functions of BOSS.

In the ```data/``` directory, we provide:
- Isotropic 2PCF, 3PCF and full/disconnected 4PCF measurements from BOSS in the CMASS-NGC and CMASS-SGC regions.
- Full/disconnected 4PCF measurements from 1000 MultiDark-Patchy mocks in the CMASS-NGC and CMASS-SGC regions.
- Analytic covariance matrices for the NGC and SGC regions, derived assuming Gaussianity, isotropy and a uniform survey geometry in Hou et al. (2021, [arXiv](https://arxiv.org/abs/2108.01714)).

All data are computed using the [encore](https://github.com/oliverphilcox/encore) code of [Philcox et al. 2021a](https://arxiv.org/abs/2105.08722). The main analysis is done in the [Jupyter Notebook](https://github.com/oliverphilcox/Parity-Even-4PCF/blob/main/BOSS%20Even-Parity%204PCFs.ipynb).

For questions, contact [Oliver Philcox](mailto:ohep2@cantab.ac.uk).
