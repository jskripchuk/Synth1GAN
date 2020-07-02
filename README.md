# This Synth1 Bank Does Not Exist
Local man tries to learn PyTorch before going to graduate school.

# How to Use
1) `create_csv.ipynb` is used to generate a CSV file from the big folder of presets `synth_patches`
2) The first half of`feature_engineering.ipynb` cleans up the data, normalizes it, and puts it in a form to be fed into the model.
3) `synth_gan_gp.ipynb` takes that normalized data, trains a WGAN GP on it, and spits out generated batches in `wgan_gp_final`
4) The second half of `feature_engineering.ipynb` has some code to turn a .csv file in `wgan_gp_final` into a Synth1 Preset folder that you can load into Synth1.
