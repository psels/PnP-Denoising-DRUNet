# PnP-Denoising-DRUNet

This project explores selfsupervised denoising of correlated noise using Drunet.

While modern denoisers (e.g. blind-spot networks) perform well under the assumption of i.i.d. Gaussian noise, real-world noise is often spatially correlated, causing self-supervised losses to fail.

The goal of this project is to extend self-supervised Gaussian denoising frameworks to correlated noise settings, without requiring ground-truth data.
