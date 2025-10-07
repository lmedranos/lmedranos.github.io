---
layout: page
title: "Research"
description: "Physical chemistry / Materials science / Machine learning"
header-img: "img/lms/gb.jpg"
category: projs
---

## EquiDTB: Augmenting DFTB with machine learning
Density functional tight-binding (DFTB) method is a semi-empirical method that provides access to electronic, structural, and vibrational properties of large and complex molecules requiring only a fraction of the computational cost of density functional theory methods. EquiDTB model has improved the accuracy of DFTB3 method, achieving hybrid DFT-PBE0 level, by replacing the standard pairwise repulsive potentials with many-body equivariant neural network potentials. I have created the <a href="https://github.com/lmedranos/EquiDTB" target="_blank" style="color: blue;">EN4TB Github repository</a> where you can find the NN potentials and scripts to run simulations of molecular systems. 


<p align="center">
  <img src="{{ site.url }}/img/research/tp1/equidtb.png" alt="Leonardo" width="500"/>
</p>

## Quantum-mechanical datasets
Implementing robust pipelines for generating comprehensive and highly accurate QM datasets of drug-like molecules/biomolecules is of crucial relevance for the development of reliable AI models. During the last years, I contributed to the generation, curation, formatting, and analysis of extensive benchmark datasets of organic molecules such as QM7-X, Aquamarine, GEMS, QUID, and MORE-Q. More details about these datasets can be found in the associated  publications. 

<p align="center">
  <img src="{{ site.url }}/img/research/tp2/aqm.png" alt="Leonardo" width="500"/>
</p>

## "Freedom of design" in chemical spaces
Comprehensive analyses of large datasets are crucial for determining structure-property and property-property relationships of organic molecules. Recently, I exhaustively examined QM7-X dataset, finding an intrinsic “freedom of design” in the molecular property space spanned by small organic molecules, and uncovering molecular design rules that follow physical and chemical intuition. These insights were later used to the successful implementation of a generative framework using variational autoencoders (known as the QIM model), which allowed to map QM properties to 3D structures for small molecules. 
<p align="center">
  <img src="{{ site.url }}/img/research/tp3/fod.png" alt="Leonardo" width="500"/>
</p>

## ADMET prediction
ML approaches have drastically advanced the exploration of structure-property and property-property relationships in computer-aided drug discovery. A central challenge in this field is the identification of molecular descriptors that can effectively capture both geometric- and electronic structure-derived features, enabling the development of reliable and interpretable predictive models. While numerous descriptors focusing solely on structural characteristics have been recently proposed, improvements in model accuracy often come at the cost of increased computational demands, thereby restricting their practical applicability. To address this challenge, we have developed the “QUantum Electronic Descriptor” (QUED) framework, which integrates both structural and electronic data of molecules to develop ML regression models for property prediction (see <a href="https://github.com/lmedranos/QUED" target="_blank" style="color: blue;">QUED Github repository</a>). 

<p align="center">
  <img src="{{ site.url }}/img/research/tp4/QMdescriptors.png" alt="Leonardo" width="500"/>
</p>

<!--
## Transport in low-dimensional materials
-->

