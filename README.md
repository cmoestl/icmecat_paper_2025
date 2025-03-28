# ICMECAT paper 2025

Code for producing the results and figures for the Möstl et al. 2025 ICMECAT paper.

Everything is produced with the notebook moestl_icmecat_results.ipynb, see instructions on top of this file.

Environment is helio5, see /envs.

## Installation

Install python with miniconda:

on Linux:

    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    bash Miniconda3-latest-Linux-x86_64.sh

on MacOS:

    curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
    bash Miniconda3-latest-MacOSX-x86_64.sh


go to a directory of your choice

    git clone https://github.com/cmoestl/icmecat_paper_2024

Create a conda environment using the "envs/env_helio5.yml", and activate the environment:

    conda env create -f env_helio5.yml

    conda activate helio5
