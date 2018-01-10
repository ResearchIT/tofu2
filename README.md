# Singularity Recipe for Tofu2

This repo contains recipes to run [Tofu2](https://github.com/PacificBiosciences/IsoSeq_SA3nUP/wiki/%5BBeta%5D-ToFU2:-running-and-installing-ToFU2#install)
within a [Singularity](http://singularity.lbl.gov/) container, which can be built 
using [Singularity Hub](https://singularity-hub.org/)

Versions:

* v17 - Tofu2 installed on Ubuntu

## How to Use:

Run example:

singularity run shub://ResearchIT/tofu2 run_preCluster.py --cpus=4 

## Alternative method:
use the provided bash wrapper and module file to use the tofu2 singularity container like a standard module
(this assumes you have a singularity/2.4 module)

e.g.

module load tofu2/v17
tofu2 run_preCluster.py --cpus=4
