# msm-rna-fraying

This repository contains tools and trajectories described in the following paper:

Pinamonti, Paul, Noè, Rodriguez, and Bussi,
*The mechanism of RNA base fraying: molecular dynamics simulations analyzed with core-set Markov state models*,
submitted (2018)

Preprint available at [arXiv:1811.12144](https://arxiv.org/abs/1811.12144).

## Trajectories

Clone this repository including all trajectory files:
````
git clone --recursive https://github.com/bussilab/msm-rna-fraying.git
````

Clone only this repository and then download files for specific systems
````
git clone https://github.com/bussilab/msm-rna-fraying.git
cd msm-rna-fraying
git submodule update desres-ucgc
git submodule update amber-ucgc
````
