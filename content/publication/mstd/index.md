---
title: "A Spiking Neural Network Model for Visual Motion Perception"
authors:
- admin
- Michael Beyeler
- Jeffrey Krichmar
doi: ""
date: "2019-10-21"

weight: 1

abstract:
 <em>A spiking neural network model of macaque MSTd. MSTd-like response properties emerged from evolving STDP and homeostatic scaling parameters in the network. [Poster](../../files/sfn2019.pdf) presented at *Society for Neuroscience*, Chicago, 2019.</em> <br><br>

 Receiving direct input from the medial temporal (MT) area, the dorsal part of the medial superior temporal (MSTd) area is believed to play a key role in visual motion processing. A previous study demonstrated that several neurophysiological response properties of MSTd, such as 3D translation and rotation selectivity, emerge from applying a dimensionality reduction technique known as Nonnegative Matrix Factorization (NMF) to MT-like activity patterns. It was hypothesized that spike-timing dependent plasticity and homeostatic synaptic scaling (STDP-H) in Spiking Neural Networks (SNNs) performs a similar function as NMF. To test this hypothesis, we implemented a SNN model of macaque MT/MSTd, utilizing an evolutionary algorithm to optimize the parameters of STDP-H. Performance was measured by how well the SNN reconstructed flow pattern stimuli. In the network, each MT neuron was tuned to a speed of 1m/s and one of 8 different directions of movements, and had a receptive field of 1 pixel radius, subtending ~3° of visual angle. During training, simulated flow fields were fed into the network and STDP-H updated the connection weights between groups. By multiplying the MT to MSTd connection weights and MSTd activations, we were able to reconstruct MT activity patterns (the reconstructed MT and the input MT neuronal firing rates have a correlation of 0.68±0.11), and recover the flow field stimuli with high fidelity. The MSTd neurons appeared to have 3D translation and rotation selectivity resembling neurophysiological data, and each neuron spanned only a subregion of the visual field, preferring a mixture of translational and rotational flow components. The model accurately captured the 3D visual response properties of MSTd and indicated that STDP-H is indeed performing a form of dimensionality reduction.




#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
#url_pdf: 
#url_code: ''
#url_dataset: ''
url_poster: files/sfn2019.pdf
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
 focal_point: ""
 preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
