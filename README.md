# Machine-Learning-and-the-Hubbard-model
Here is some code and pdf report on applying machine learning to density functional theory and the Hubbard model.

# HubbardClass.py
This python script can be downloaded and used as a template for generating the Hamiltonian matrix for the Hubbard model with specified parameters. It will work in 1D and 2D though if one wishes the extension to 3D should be easy to do by extending the 2D methods within.

# grandcanonical.ipynb
This jupyter notebook was then written to generate many instances of the Hubbard model for randomly chosen parameters, and data about such things as the site occupations of the model etc along with the ground state energy was stored. In this case however due to the fact I considered the grand canonicl ensemble, it was the grand potential or Landau free energy that was stored. If one wished to study either the microcanonical or canonica ensembles this code could be simplified as such to suit.

The final notebook the repository contains the use of tensorflow to learn the relationships described in the pdf file attached. For a detailed description of the aims of this project I suggest you read this pdf. 
