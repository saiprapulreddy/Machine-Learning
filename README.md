Project Title

Comparative Analysis of Adversarial Loss Functions in ResNet-Based GANs on CIFAR-10

Project Overview

This repository accompanies a tutorial and experimental study evaluating how different adversarial loss functions influence the behaviour and performance of Generative Adversarial Networks (GANs). Using a shared SNGAN-style ResNet generator and discriminator, the project compares three widely used objectives: the original non-saturating GAN loss, the Wasserstein GAN (WGAN) loss with weight clipping, and the hinge loss.
The purpose of this study is to isolate the effect of the loss function by keeping architecture, dataset, and optimisation settings constant. Evaluation includes training-curve analysis, qualitative inspection of generated samples, and quantitative measures such as FID. Results demonstrate that hinge loss provides the most stable optimisation and highest visual fidelity, whereas naive WGAN with clipping shows severe instability.

Repository Structure

24100264_machine learning_code.ipynb

The repository contains:

Tutorial PDF presenting the full written assignment

Jupyter Notebook used to train all models and generate figures

Figures folder containing loss plots, sample grids, and architecture diagrams

Licence file (MIT)

This README

How to Use the Notebook

https://github.com/saiprapulreddy/Machine-Learning.git

Machine-Learning

Install the required Python packages.

Open the provided Jupyter notebook.

Run all cells sequentially to:

Train three GAN variants

Generate sample images for each loss function

Produce loss-curve figures

Compute FID scores

Save all outputs to the figures directory

All images and results included in the tutorial were produced directly from this notebook.

Dataset Information

The CIFAR-10 dataset is used for all experiments. It contains 60,000 colour images across ten object categories with a resolution of 
32
×
32
32×32. The dataset is well suited for evaluating GANs due to its diversity and moderate complexity. Images are normalised to match the generator’s output range, and no further preprocessing is required.

Accessibility Statement

This project follows accessibility-friendly practices:

All figures include descriptive alt text

Colour-blind-safe palettes are used for all plots

High-contrast visual styles enhance readability

Structured headings improve screen-reader compatibility

No information is conveyed by colour alone

Licence

This project is released under the MIT Licence, permitting reuse, modification, and distribution with attribution.
