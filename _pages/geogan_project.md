---
permalink: /geogan_project/
title: "GEOGAN project"
layout: splash
classes: wide
author_profile: false
toc: true
toc_sticky: true
search: true
header:
  overlay_filter: "0.2"
  overlay_image: /assets/images/AI4NZ_banner3.png # cluster-4.png
  overlay_text: ""

gallery1:
  - url: /assets/project_images/non-stationary1.jpg
    image_path: assets/project_images/non-stationary1.jpg
    alt: "generated non-stationary fields"

  - url: /assets/project_images/non-stationary2.jpg
    image_path: assets/project_images/non-stationary2.jpg
    alt: "generated non-stationary fields"

---
## Representation and Generation of stochastic fields using GANs
Deep learning techniques, particularly those that manage high-dimensional spatial data, are gaining traction for computational applications similar to their role in computer vision. Among these techniques, generative adversarial networks (GANs) have emerged as a promising tool for the parametrization and synthesis of spatial geological models. GANs efficiently learns a neural network parametrization of the geology —referred to as a generator network— that is capable of reproducing very complex geological patterns with dimensionality reduction of several orders of magnitude. In this project, we address three main challenges of using GANs for representing stochastic geological fields: (a) efficient training under limited data, (b) handling non-stationary field generation, and (c) generation of large-scale models on commodity GPUs with limited memory. This project is funded by TotalEnergies with the aim of understanding the impact of geological uncertainties on the safe storage of CO2 in deep geological formations.


{% include gallery id="gallery1" layout="half" caption="Sample of generated non-stationary fields using conditional GANs." %}

## Project team at Heriot-Watt University (HWU)
- Principal Investigator: [Ahmed H. Elsheikh](https://researchportal.hw.ac.uk/en/persons/ahmed-h-elsheikh)
- Former PhD student: Alhasan Abdellatif

## Project Publications
- Alhasan Abdellatif, Ahmed H. Elsheikh, **Generating Infinite-Resolution Texture using GANs with Patch-by-Patch Paradigm**,
arXiv preprint (2023). [URL](https://arxiv.org/abs/2309.02340)
- Alhasan Abdellatif, Ahmed H. Elsheikh, Daniel Busby, Philippe Berthet, **Generation of non-stationary stochastic fields using Generative Adversarial Networks**, arXiv preprint (2022). [URL](https://arxiv.org/abs/2205.05469)
- Alhasan Abdellatif, Ahmed H Elsheikh, Gavin Graham, Daniel Busby, Philippe Berthet, **Generating unrepresented proportions of geological facies using Generative Adversarial Networks**, Computers & Geosciences, Volume 162, (2022). [URL](https://doi.org/10.1016/j.cageo.2022.105085)

## Prior Publications
- Chan, S., Elsheikh, A.H., **Parametrization and generation of geological models with generative adversarial networks.** arXiv preprint (2017). [URL](https://arxiv.org/abs/1708.01810)
- Chan, S., Elsheikh, A.H., **Parametric generation of conditional geological realizations using generative neural networks.** Computational Geosciences, volume 23, 925–952 (2019). [URL](https://doi.org/10.1007/s10596-019-09850-7)
- Chan, S., Elsheikh, A.H., **Parametrization of Stochastic Inputs Using Generative Adversarial Networks With Application in Geology**, Frontiers in Water, volume 2, pages 5 (2020). [URL](https://doi.org/10.3389/frwa.2020.00005)