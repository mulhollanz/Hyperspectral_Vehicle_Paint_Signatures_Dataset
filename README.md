# Hyperspectral Vehicle Paint Signatures 
This page contains all the links for our paper: Mulhollan, Zachary, et al. "Calibrated Vehicle Paint Signatures for Simulating Hyperspectral Imagery." arXiv preprint arXiv:2004.08228 (2020) ([link](https://arxiv.org/pdf/2004.08228.pdf))

We fly a series of drone flights over a parking lot at Rochester Institute of Technology, a small extract of which can be seen here:
![image_flight_line](/images/img_flight_line.png)

We then extract information from the sensors and pass it through a bunch of calibration modules to obtain the final radiance calibrated paint signatures. We use these signatures to further simulate a parking lot scene in DIRSIG[1], the image below shows the rendered scene with corresponding real car templates:

![image_dirsig_sim](/images/img_paint_egs.png)

### *NOTE:*
We are working towards validating and organizing the data and will add all information here as early as possible.

### References:
[1] Adam A Goodenough and Scott D Brown. Dirsig5: nextgeneration remote sensing data and image simulation framework. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 10(11):4818–4833, 2017.
