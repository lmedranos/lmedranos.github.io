---
layout: page
title: "Research"
description: "Physical chemistry / Materials science / Machine learning"
header-img: "img/lms/gb.jpg"
category: projs
---

## EquiDTB: Augmenting DFTB with machine learning
Density functional tight-binding (DFTB) method is a semi-empirical method that provides access to electronic, structural, and vibrational properties of large and complex molecules requiring only a fraction of the computational cost of density functional theory methods. <a href="https://chemrxiv.org/engage/chemrxiv/article-details/68095e1d927d1c2e667c750a" target="_blank" style="color: blue;">EquiDTB model</a> has improved the accuracy of DFTB3 method, achieving hybrid DFT-PBE0 level, by replacing the standard pairwise repulsive potentials with many-body equivariant neural network potentials. I have created the <a href="https://github.com/lmedranos/EquiDTB" target="_blank" style="color: blue;">EquiDTB Github repository</a> where you can find the NN potentials and scripts to run simulations of molecular systems. 


<p align="center">
  <img src="{{ site.url }}/img/research/tp1/equidtb.png" alt="Leonardo" width="500"/>
</p>

## Quantum-mechanical datasets
Implementing robust pipelines for generating comprehensive and highly accurate QM datasets of drug-like molecules/biomolecules is of crucial relevance for the development of reliable AI models. During the last years, I contributed to the generation, curation, formatting, and analysis of extensive benchmark datasets of organic molecules such as <a href="https://www.nature.com/articles/s41597-021-00812-2" target="_blank" style="color: blue;">QM7-X</a>, <a href="https://www.nature.com/articles/s41597-024-03521-8" target="_blank" style="color: blue;">Aquamarine</a>, <a href="https://www.science.org/doi/full/10.1126/sciadv.adn4397" target="_blank" style="color: blue;">GEMS</a>, <a href="https://www.nature.com/articles/s41467-025-63587-9" target="_blank" style="color: blue;">QUID</a>, and <a href="https://www.nature.com/articles/s41597-025-04616-6" target="_blank" style="color: blue;">MORE-Q</a>. More details about these datasets can be found in the associated  publications. 

<p align="center">
  <img src="{{ site.url }}/img/research/tp2/aqm.png" alt="Leonardo" width="500"/>
</p>

## "Freedom of design" in chemical spaces
Comprehensive analyses of large datasets are crucial for determining structure-property and property-property relationships of organic molecules. Recently, I exhaustively examined QM7-X dataset, finding an intrinsic <a href="https://pubs.rsc.org/en/content/articlelanding/2023/sc/d3sc03598k" target="_blank" style="color: blue;">“freedom of design”</a> in the molecular property space spanned by small organic molecules, and uncovering molecular design rules that follow physical and chemical intuition. These insights were later used to the successful implementation of a generative framework using variational autoencoders (known as the  <a href="https://www.nature.com/articles/s41467-024-50401-1" target="_blank" style="color: blue;">QIM model</a>), which allowed to map QM properties to 3D structures for small molecules. 
<p align="center">
  <img src="{{ site.url }}/img/research/tp3/fod.png" alt="Leonardo" width="500"/>
</p>

## ADMET prediction
A central challenge in computer-aided drug discovery is the identification of molecular descriptors that can effectively capture both geometric- and electronic structure-derived features, enabling the development of reliable and interpretable predictive models. While numerous descriptors focusing solely on structural characteristics have been recently proposed, improvements in model accuracy often come at the cost of increased computational demands, thereby restricting their practical applicability. To address this challenge, we have developed the <a href="https://chemrxiv.org/engage/chemrxiv/article-details/68c61dd73e708a7649eb1250" target="_blank" style="color: blue;">“QUantum Electronic Descriptor” (QUED) framework</a>, which integrates both structural and electronic data of molecules to develop ML regression models for property prediction (see <a href="https://github.com/lmedranos/QUED" target="_blank" style="color: blue;">QUED Github repository</a>). 

<p align="center">
  <img src="{{ site.url }}/img/research/tp4/QMdescriptors.png" alt="Leonardo" width="500"/>
</p>


## Transport in low-dimensional materials
A crucial goal for increasing thermal energy harvesting will be to progress towards atomistic design strategies for smart nanodevices and nanomaterials. This requires the combination of computationally efficient atomistic methodologies with quantum and classical transport based approaches. In this reagard, we have employed nonequilibrium molecular dynamics (NEMD) simulations to investigate the influence of heat flux asymmetries in thermodynamic properties. Moreover, to address quantum ballistic thermal transport in nanoscale systems, we implemented a nonequillibrium Green’s functions (NEGF) treatment of transport combined with a density-functional based approach. 

<p align="center">
  <img src="{{ site.url }}/img/research/tp5/topic5.png" alt="Leonardo" width="500"/>
</p>

