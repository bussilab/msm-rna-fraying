# msm-rna-fraying

This repository contains tools and trajectories described in the following paper:

Pinamonti, Paul, Noè, Rodriguez, and Bussi,
*The mechanism of RNA base fraying: molecular dynamics simulations analyzed with core-set Markov state models*,
[J. Chem. Phys. 150, 154123 (2019)](https://doi.org/10.1063/1.5083227) ([arXiv:1811.12144](https://arxiv.org/abs/1811.12144)).

## Trajectories

Clone this repository including all trajectory files:
````
git clone --recursive https://github.com/bussilab/msm-rna-fraying.git
````

Clone only this repository and then download files for specific systems
````
git clone https://github.com/bussilab/msm-rna-fraying.git
cd msm-rna-fraying
git submodule update --init desres-ucgc
git submodule update --init amber-ucgc
````
