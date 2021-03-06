# MLTSA-V1

Version 1 of the repository for the Unbinding-MLTSA, this code corresponds to the bioRxiv preprint: https://www.biorxiv.org/content/10.1101/2021.09.08.459492v1

Compatible with [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pedrojuanbj/MLTSA-V1/main)

__Combined free energy calculation and machine learning methods for understanding ligand unbinding kinetics.__ 
*Magd Badaoui, Pedro J Buigues, Dénes Berta, Gaurav M. Mandana, Hankang Gu, Callum J Dickson, Viktor Hornak, Mitsunori Kato, Carla Molteni, Simon Parsons, Edina Rosta
bioRxiv 2021.09.08.459492; doi: https://doi.org/10.1101/2021.09.08.459492*


# Analytical Model example

Under __"MLTSA_examples/OneD_pot/"__ the file __"OneD_sklearn_example.ipynb"__ is a Jupyter Notebook going through the basics 
of generating the one dimensional data and subsequent features for the ML. It contains code for the training, testing 
and global mean calculation as well as the Accuracy Drop for feature selection. 

You can run this example using [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pedrojuanbj/MLTSA-V1/main)

# Main Code 

- __"MLTSA_sklearn/MLTSA_sk.py"__ : Contains the main code for calculating the Global Means and subsequent Accuracy Drop 
calculation as well as a wrapping function for plotting nicely the outcome of the approach.  

- __"MLTSA_sklearn/models.py"__ : Contains a wrapping function for an easy train/test of almost any Sklearn classifier. 

- __"MLTSA_examples/OneD_pot/OneD_pot_data.py"__ : Contains the main code for generating simulations on 1D potentials
(Single-well and Double-well) and prepare a dataset with the desired number of features. It has functions to generate 
data on demand based on the   

# Animated Trajectories

GIF files for each system are available under the __"Animated_Trajectories"__ folder.

Otherwise see here: 

- ## 3sw4:
![Alt Text](Animated_Trajectories/3sw4_rep1_close.gif)

![Alt Text](Animated_Trajectories/3sw4_rep2_close.gif)

![Alt Text](Animated_Trajectories/3sw4_rep3_close.gif)


- ## 4fkw:
![Alt Text](Animated_Trajectories/4fkw_rep1_close.gif)

![Alt Text](Animated_Trajectories/4fkw_rep2_close.gif)

![Alt Text](Animated_Trajectories/4fkw_rep3_close.gif)


- ## 4fku:

![Alt Text](Animated_Trajectories/4fku_rep1_close.gif)

![Alt Text](Animated_Trajectories/4fku_rep2_close.gif)

![Alt Text](Animated_Trajectories/4fku_rep3_close.gif)
