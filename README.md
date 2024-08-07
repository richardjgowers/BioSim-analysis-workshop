# Molecular Dynamics Simulation and Analysis workshop

## Instructors
    
- [Dr Matteo Degiacomi, Durham University (MTD)](https://degiacomi.org)
- [Dr Antonia Mey, University of Edinburgh (AM)](https://mey-research.org/)  

## Schedule

L1-8: Lectures. P: practical.

### Unit 1: Simulation Preparation

| Session                            | Materials |
|------------------------------------|-----------|
| L1: Introduction to Proteins | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/1_Introduction/Lecture_1_Introduction.pdf) | 
| L2: Understanding Protein Systems | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/2_Protein_Preparation/Lecture_2_Protein_Prep.pdf)
| P: Understanding Protein Systems, contd. | [Webserver](https://server.poissonboltzmann.org/pdb2pqr)|
| L4: Protein-Ligand Docking                 |  [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/3_Docking/Lecture_3_Docking.pdf)| 
| P: Protein-Ligand Docking                 |  [![Docking](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/3_Docking/3_Docking.ipynb)| 
| L3: Simulation Setup          | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/4_Simulation_Setup/Lecture_4_Simulation_setup.pdf) |
| P: Simulation Setup          | [![Simulation](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/4_Simulation_Setup/4_Simulation_Setup.ipynb) |


### Unit 2: Simulation Anaylsis


| Session                                             | Materials |
|-----------------------------------------------------|-----------|
| L5: Simulation Basic Analyses             | [Lecture Slides](5_Analysis_MDAnalysis/Lecture_5_Analysis_MDAnalysis.pdf)|
| P: Simulation Basic Analyses             | [![Analysis_0](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/5_Analysis_MDAnalysis/5_Analysis_MDAnalysis.ipynb)|
| L6: Dimensionality Reduction                  | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/6_Analysis_DR/Lecture_6_DR.pdf)  |
| P: Dimensionality Reduction, part 1           |  [![Analysis_1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/6_Analysis_DR/6_Analysis_part1.ipynb)|
| P: Dimensionality Reduction, part 2           | [![Analysis_2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/6_Analysis_DR/6_Analysis_part2.ipynb)|
| L7: Clustering   | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/7_Analysis_clustering/Lecture_7_Clustering.pdf)|
| P: Clustering   | [![Analysis_3](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/7_Analysis_clustering/7_clustering.ipynb) |
| L8: Data Classification    | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/8_Analysis_classification/Lecture_8_classification.pdf) | 
| P: Data Classification  | [![Analysis_4](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/8_Analysis_classification/1_classification.ipynb) |
| L9: Markov State Modelling  | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/9_Analysis_MSM/Lecture_9_MSM.pdf) |


## Google Colab

The workshop is designed to run on Google Colab and all workshop notebooks run directly from your browser, no installation is required. In particular, please note that the Open Force Field material in the Jupyter notebook of session [4_Simulation_Setup](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/4_Simulation_Setup) will not natively run on Windows machines. For extra information [see here](https://docs.openforcefield.org/en/latest/install.html#openff-on-windows).

## Setting up your own Python environment 

<!--The workshop will be in a blended learning environment and hands-on. You will need a working installation of MDAnalysis and related packages including data to analyze in order to participate. The full installation may take up to about 1 GB of space (mostly for data, which you can delete after the workshop).--> 

Instructions for setting up your environment to run this workshop locally
are provided in [`INSTALL.md`](INSTALL.md).

A full list of the required Python packages can be seen inside [`environment.yml`](environment.yml).

To avoid waiting for everyone's setup to be up and running we highly recommend trying this workshop on colab and only once you are back at home and want to explore further to try and run it on your local machine. 

## Course pre-requisites

The course assumes that attendees have a working knowledge of [Jupyter notebooks](https://jupyter-notebook.readthedocs.io/en/stable/), Python (especially the [NumPy library](https://numpy.org/), and the bash shell.


## Licenses

<!--TBA-->

- The MDAnalysis logo and its derivatives are licensed under the [Creative Commons Attribution-NoDerivs 3.0 Unported License](https://creativecommons.org/licenses/by-nd/3.0/).
- The MDAnalysis material in folder [5_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/5_Analysis_MDAnalysis) is licenced under CC-BY 4.0 
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" title='This work is licensed under a Creative Commons Attribution 4.0 International License.' align="right"/></a>
- The Docking material in folder [3_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/3_Docking) is licensed under and Apache-2.0 and MIT license.
- The Open Force Field material in folder [4_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/4_Simulation_Setup) is licensed under MIT license.
- Material in folders [1_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/1_Introduction),
[2_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/2_Protein_Preparation),
[6_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/5_Analysis_DR),
[7_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/6_Analysis_clustering)
[8_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/8_Analysis_classification), and
[9_\*](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/tree/main/9_Analysis_MSM) is licenced under CC-BY-SA 4.0.
<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="width=50" src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" title='This work is licensed under a Creative Commons Attribution 4.0 International License.' align="right"/></a>


## Acknowledgements

Please see [`AUTHORS.md`](AUTHORS.md) for a list of contributors to the workshop materials.
