Preparation:

1. Install Python 2.7 and required libraries. OBS! You need Python 2.7 (not 3.x)

   The easiest option is to install Anaconda: https://www.continuum.io/downloads

   Many libraries are install by default when installing Anaconda.
   However, matplotlib and Keras need to be installed (even if the first part can be done without Keras, 
	and the rest without matplotlib, if skipping the visualizations).
   conda install matplotlib
   pip install keras

2. Install Jupyter notebook, http://jupyter.readthedocs.io/en/latest/install.htm

3. Test your installations by making sure that the following imports do not throw any errors:

(Start a notebook by typing "jupyter notebook" in the terminal, then create a new Python 2.7 notebook 
and copy the imports to a cell. Run.
OBS: If you already have python 3.x installed, you might have to change python environment before starting a notebook.
Type "activate py27" in the terminal.)

import numpy as np
import matplotlib.pyplot as plt
import numpy as np
import Keras





