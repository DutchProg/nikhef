# Dataframes

Info about the dataframes in this directory
Please feel free to contact me on Slack or via email for info if you need to use them

mail: cfuselli@nikhef.nl
slack: Carlo Fuselli




## BiPo

### Beta

#### beta_selection_214bi_sr0_bkg.h5 (OLD!!)

This is the main beta selection dataframe. 
Tolerance window = 2mus
Selection based on number of S2s and S1/S2s ratios. 
The dataframe defore the two cuts is 

#### beta_selection_214bi_sr0_bkg_new.h5

Same as previous but with more runs!

This is the main beta selection dataframe. 
Tolerance window = 2mus
Selection based on number of S2s and S1/S2s ratios. 
The dataframe before the two cuts is bipo_new_all_bkg.h5

#### beta_selection_214bi_sr0_bkg_new_3mus.h5

Same as previous but with more runs!

This is the main beta selection dataframe. 
Tolerance window = 2mus
Selection based on number of S2s and S1/S2s ratios. 
The dataframe before the two cuts is bipo_new_all_bkg_3mus.h5

### All

#### bipo_new_all_bkg.h5

It's the mother of beta_selection_214bi_sr0_bkg_new.h5 
Before the cuts to select pure beta events. 
Contains all the sr0 runs. 

#### bipo_new_all_bkg_3mus.h5

It's the mother of beta_selection_214bi_sr0_bkg_new_3mus.h5 
Before the cuts to select pure beta events. 
Contains all the sr0 runs. 
Tolerance window is now 3mus. 

#### bipo_only_two_s2.h5

Not to use. Just a test. 
Checking what happens to the unmatched evetns with only two S2s. 


## Others

#### bkg_cut_width_ss_fv.h5

Background data, cut single scatter and cut fiducial volume strict
Used to check Micha's 2vbb band and compare with beta band

#### rn_cut_width_ss_fv.h5

Radon data, cut single scatter and cut fiducial volume strict
Used to check Micha's 2vbb band and compare with beta band