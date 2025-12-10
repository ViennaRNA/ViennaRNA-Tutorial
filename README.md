# ViennaRNA-Tutorial

Welcome to the GitHub page of the ViennaRNA tutorial.


Here, you will find a collection of Jupyter notebooks that explain the basic functions of the ViennaRNA package and demonstrate its application by replicating the results of recent publications. The notebooks contain detailed explanations, as well as a series of small tasks to test the concepts introduced. Please feel free to share the tutorial to others.


This repository contains two branches. The 'with_solution' branch contains notebooks with example solutions for the provided tasks, whereas those solutions are absent in the main branch.

## List of Files

| File-Name | Content |
| --------- | ------- |
| 1_ViennaRNA_Introduction.ipynb | Contains an introduction to the command line tools and the Python API of the ViennaRNA package. |
| 2_Practical_Example.ipynb | Contains the replication of a pipeline introduced in the paper [[von Löhneysen et al. - 2023]](https://journals.sagepub.com/doi/pdf/10.1089/cmb.2024.0519) which uses soft and hard constraints. |

## Installation

The detailed requirements and dependencies are noted at the start of each notebook. We recommend using Conda to install the ViennaRNA package and other Python libraries. Alternatively, all notebooks are designed to work in a Google Colab environment.

```bash
conda create env -f viennarna-tutorial.yml
```

For Windowns users, please install Windows Subsystem for Linux (WSL), and use it to pretend you’re a perfectly normal Linux user. See [this page](https://learn.microsoft.com/en-us/windows/wsl/install) for more details.

For users who prefer to use Google Colab, please run below code from Google Colab to install needed packages

```bash
!pip install ViennaRNA
!apt-get update -qq
!apt-get install -y vienna-rna
!apt install imagemagick
!rm /etc/ImageMagick-6/policy.xml
```

