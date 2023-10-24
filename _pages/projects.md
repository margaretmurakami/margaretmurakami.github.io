---
title: "Projects"
permalink: /projects/
layout: splash
entries_layout: grid
author_profile: true

feature_row:
  - image_path: assets/images/greenlandRadar.jpeg
    image_caption: "Courtesy CReSIS"
    alt: "GrIS Inverse Problem"
    title: "Bayesian Inverse Methods for Ice Sheet Model Calibration and Reconstruction"
    excerpt: "Calibrating ice sheet model SICOPOLIS using age layer radar data in order to project the future impact on sea level accurately."
    url: /greenlandInversion/
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_1:
  - image_path: /assets/images/mitgcmFKB.jpeg
    image_caption: "Courtesy [An T. Nguyen](https://oden.utexas.edu/people/1464/)"
    alt: "MITgcm with FKB"
    title: "Deep Learning Emulator for the dynamics of sea ice within the MITgcm model"
    excerpt: "Can we reduce the computational costs of dynamic sea ice models using Deep Learning?"
    url: /MITgcm_FKB/
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_2:
  - image_path: assets/images/stampede2.jpeg
    image_caption: "Courtesy TACC"
    alt: "TNT course project"
    title: "Laplacian 2D Finite Difference (FD) solver on Stampede2 Supercomputer"
    excerpt: "Leveraged TACC's Stampede2 Supercomputer to build a heat equation solver."
    url: /TNT/
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_3:
  - image_path: /assets/images/PINN.jpeg
    image_caption: "Image from L.Lu et. al (2019)"
    alt: "PINN"
    title: "Deep Mountain Glaciers"
    excerpt: "Leveraging Deep Learning to emulate as well as invert non-linear, highly diffusive mountain glacier model."
    url: /PINN/
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_4:
  - image_path: assets/images/inverseProblem.jpeg
    image_caption: "Image from Isaac et. al (2015)"
    alt: "Inverse Problems Course"
    title: "Solving PDE-constrained inverse problems using FEniCS"
    excerpt: "Solved ill-conditioned inverse problems using the adjoint equations and special second order methods."
    url: /FEniCS
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_5:
  - image_path: /assets/images/MLgeophysics.jpeg
    image_caption: "Seismic data courtesy of NAMSS"
    alt: "ML applications in geophysics"
    title: "Machine Learning applications in geophysics"
    excerpt: "Explored utility of autoencoders, GANs, CNNs, ML algorithms across multiple applications in geophysics."
    url: /ML_geo/
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_6:
  - image_path: /assets/images/UQ.jpeg
    alt: "UQ in Computational Models"
    title: "Uncertainty Quantification in Computational Models"
    excerpt: "Using Bayesian framework to quantify uncertainties in model parameters."
    url: /UQ/
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row type="left"%}
{% include feature_row id="feature_row_1" type="right" %}
{% include feature_row id="feature_row_2" type="left" %}
{% include feature_row id="feature_row_3" type="right" %}
{% include feature_row id="feature_row_4" type="left" %}
{% include feature_row id="feature_row_5" type="right" %}
{% include feature_row id="feature_row_6" type="left" %}
w
