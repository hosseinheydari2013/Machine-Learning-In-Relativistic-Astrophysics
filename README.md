# Machine-Learning-In-Relativistic-Astrophysics

This repo shows the typical example of using Machine Learning in Astrophysics. The base code was part of the subsidiary data science workshop of ICRANET-ISFAHAN conference held ONLINE on Nov. 2021. The base code is modified in order to find the answer to the following questions: 
1. Is there any difference in the accuracy of the decision trees between quasi-stellar objects (QSO) and regular Galaxies ? 
2. What will be the best fraction of split and test data? 

## QSOs vs Galaxies
>You might be surprised to learn that our sample of galaxies consists of two different populations: regular galaxies and quasi-stellar objects (QSOs). QSOs are a type of galaxy that contain an actively (and intensly) accreting supermassive black hole. This is often referred to as an Active Galactic Nucleus (AGN).
>The light emitted from the AGN is significantly brighter than the rest of the galaxy and we are able to detect these QSOs out to much higher redshifts. In fact, most of the normal galaxies we have been using to create our models have redshifts less than z≈0.4, while the QSOs have redshifts all the way out to z≈6. Due to this contribution from the AGN, the flux magnitudes measured at different wavelengths might not follow the typical profile we assumed when predicting redshifts.


## Remarks:
1. To run the notebook you need to have access to "sdss_galaxy_colors.npy" data which is located in data directory of the current repo. 
