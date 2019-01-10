README file created on 28th Nov 2018 by RH
------------------------------------------

This folder contains Jupyer notebooks that perform the following tasks in order,

1) SETI Signal Generator  ....ipynb (simulates the basic signal types)
2) SETI train valid test sorting ....ipynb (moves the files intro usable folders)
3) SETI CNN model  ....ipynb (creates a deep learning model from the simulated data)
4) SETI Spectrograms from Open Data Filterbanks ....ipynb (creates images from raw filterbank data)
5) SETI Predict Open Data ....ipynb (uses the CNN model to make predictions on the images)

Eventually, 4 and 5 will talk to one another, to ensure only the interesting parts on an A file are converted for BACAD.