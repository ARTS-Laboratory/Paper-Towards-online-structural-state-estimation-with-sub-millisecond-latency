# Towards online structural state estimation with sub-millisecond latency

We present methods of developing and deploying long short-term memory (LSTM) models for use in on-edge devices with sub-millisecond response times.

## Model development
<p align="center">
<img src="figures/LSTM window_v3.png" alt="drawing" width="600"/>
</p>
<p align="center">
Figure 1. Sampling and computation sequence followed every timestep.
</p>

<p align="center">
<img src="figures/SNR_against_units_v4.png" alt="drawing" width="500"/>
</p>
<p align="center">
Figure 2. SNR for models with varying units, with one, two, and three cells.
</p>

## Hardware

<p align="center">
<img src="figures/ExpSetup.png" alt="drawing" width="600"/>
</p>
<p align="center">
Figure 3. Experimental setup and block diagram representation.
</p>

## Results

<p align="center">
<img src="figures/real-time prediction_v1.png" alt="drawing" width="600"/>
</p>
<p align="center">
Figure 4. Prediction from real-time setup.
</p>

<p align="center">
<img src="figures/rtos distribution_v4.png" alt="drawing" width="400"/>
</p>
<p align="center">
Figure 5. Distribution of response time for real-time system.
</p>

## Licensing and Citation

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
