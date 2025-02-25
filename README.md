This repository contains the HSC-Y3 cosmic shear 2-point correlation functions data vector and related files used in https://arxiv.org/abs/2403.20323

The cosmic shear likelihood that extends to $\theta \sim 0.3$ arcmin can be run by replacing some files in 
the public HSC Y3 likelihood (https://github.com/joezuntz/cosmosis-standard-library/blob/main/examples/hsc-y3-shear-real.ini)
as follows:

Please use "sys_model_new.py" instead of "sys_model.py," and replace "systematics.npz" with the "pp_corr_ryo.npz" file in the [add_sys_1z] module. 
Additionally, please use "data_extend_cat0.fits" for the 2pt correlation functions data vector and covariance, in place of "hsc_y3_real.fits" in the [2pt_like] module.
