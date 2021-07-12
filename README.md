# FE Migration Analysis System
Tumoursphere migraitory boundaries (TMB) are mapped out using U-Net segmentation, and its migration is modelled and quantitatively analysed

# THE WORKING PC I USED TO RUN THIS SYSTEM:
- AMD R7 3800x CPU
- 16GB 3200MHz RAM
- RTX 2080 GPU
- WINDOWS 10/11

# SOFTWARE USED FOR THIS SYSTEM:
- Python 3.7.7 (main prerequisite modules are as listed below):
  - tensorflow 2.5.0 (For tumorusphere segmentation; tensorflow installation are outlined in https://www.tensorflow.org/install; For GPU enabled cards, you can follow https://www.tensorflow.org/install/gpu)
  - GIAS 2 (For Host mesh fitting before the resultant mesh is modelled for it's migration; General instructions for the installation can be found here https://gias2-shape-modelling-tutorial.readthedocs.io/en/latest/installation.html. In my experience, python 3.7 still worked just fine)
  - numpy
  - scipy
  - opencv
  - scikit
- The latest version of FEBio (To model and and analyse the migration of the TMB)




