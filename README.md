# ExpLin
Experiments and code for the work on ExpLin, a novel saliency map generation method.

# Requirements
For running the notebooks, the following is required:
 - A Jupyter notebook system
 - The python libraries listed in "requirements.txt"
 - The ImageNet 2012 validation set (https://www.image-net.org/download.php)
 - The Oxford-IIIT Pet Dataset https://www.robots.ox.ac.uk/~vgg/data/pets/

# Experiments in this repository
 - The "Annotated Regions" experiment from the paper can be found in "Experiment_4.ipynb".
 - The "Quartile Classification" experiment from the paper can be found in Experiment_3. Use "Experiment_3_retrain.ipynb" to fine-tune the required model. Then, "Experiment_3_explain.ipynb" can be used to compute the needed scores.
 - The "Experiment_2.ipynb" notebook can be used to create the general comparison between methods. Image data will be stored appropriatly, this code was used for the overview table in the paper.
