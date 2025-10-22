# Cosmic-AI

<div align="center" style="overflow-x:auto;">

<img src='./logos/AI Institutes_News Release_logos-top.jpg' width='80%'/>
</div>

AI enhanced solutions for cosmology and astronomy. This work is supported by **NSF-Simons AI Institute for Cosmic Origins**. For more details please visit [cosmicai.org](https://cosmicai.org/) and [NSF News article](https://www.nsf.gov/news/nsf-simons-foundation-launch-2-ai-institutes-help).

Following are the current ongoing research projects:

## [CAI - Scalable Foundation Model Inference on Cloud](https://arxiv.org/pdf/2501.06249?)

A novel **Cloud-based Astronomy Inference (CAI)** framework for data parallel AI model inference on AWS. We can classify 500K astronomy images using the AstroMAE model in a minute !

<div align="center" style="overflow-x:auto;">

### Fig: CAI framework design on AWS State Machine.

<img src='./logos/cai workflow.jpg' width='50%'/>
</div>

## OmniSpectra: A Unified Foundation Model for Native Resolution Astronomical Spectra

The first foundation model to process variable lengths of spectra from arbitrary instruments at their original size/resolution, without resizing or downsampling to a fixed size. 

<div align="center" style="overflow-x:auto;">

### Fig: OmniSpectra Model Architecture.

<img src='./logos/omnispectra.jpg' width='80%'/>
</div>

## IC_pixel-diffusion

Pixel-based diffusion model for reconstructing cosmological initial conditions from Dark Matter Halos. This currently uses the main architecture from the **"Posterior Sampling of the Initial Conditions of the Universe from Non-Linear Large Scale Structures Using Score-Based Generative Models"** ([arXiv:2304.03788](https://arxiv.org/abs/2304.03788)) and optimizes it for a new observation dataset. It is trained on **Quijote Latin Hypercube simulation dataset** to reconstruct the initial condition (z = 127) from DM halo (z=0).
