# EAGOC
  Python notebook for analysing the Gap of Change modelled in ArchiMate. This is part of a thesis testing the Gap Of Change as poposed by Bakelaar et al 2017. [BakelaarRoubtsovaJoosten.pdf](BakelaarRoubtsovaJoosten.pdf)

The code in the notebook is redundant in order to be easy adaptable for certain other analytics.

A first impression is given by the [ApplicationStructureView.jpg](ApplicationStructureView.JPG) for the view of the Gap of Change.
The complete code and results of this example is in [ea_goc.pdf](ea_goc.pdf).
On page 9 counting results begins.

# Installation
Dependencies: 
- Python3
- Jupyter notebook or lab
- Pandas
- optional RISE for the slideshow

- Download or clone this repository to any system running ArchiTool, Python 3.6 and dependencies

# Use
- Run 'jupyter notebook ea_goc.ipynb' 
- The default model is the Archisurance model used in many publications.
- Changes are visualized like included picture in the repository

For a spefic model:
- Create an EA model using ArchiTool
- Export the model to csv files using a proper prefix as used in the notebook
- Run 'jupyter notebook ea_goc.ipynb'
