# Repo
Pull the repo from this location: https://github.com/jarrettalexander77/OMSCS-7641-Assignment4.

This will contain all experiments.

# Setup

I used anaconda to setup my environment for this project. As a prereq for this, all of the following packages will need setup.

- Jupyter Notebook
- Tensorflow
- Keras
- Scikit Learn
- Pandas
- Seaborn
- Matplotlib
- Numpy
- hiivemdptoolbox
- Open AI Gym

# Problems
The forest problem can be found here: https://github.com/hiive/hiivemdptoolbox/blob/master/hiive/mdptoolbox/example.py

The lake problem can be found here: https://github.com/openai/gym/blob/master/gym/envs/toy_text/frozen_lake.py

# Running the Code
All development was completed in a jupyter notebook. There are 3 notebooks - Epsilon.ipynb, Forest.ipynb, and Frozen Lake.ipynb.

These were modified heavily as testing went on. The final state should represent fairly closely the outputs in the paper.

These notebooks will generate all charts used in the report as well. They will be saved to your computer as you run them. If you want to generate all charts, you will have to update the size value.

# Notes
Some tests exist in the notebook but they do not exist in the final paper. There are evaluations of policies based on the different input parameters to the problem that are not shown in the paper. These were useful for debugging issues with the policies.
Sometimes the charts would not represent the policies accurately. However, these were omitted from the paper due to space. There are also 3 other heatmaps that were generated but those were not added either because they did not reveal very much about the problem.