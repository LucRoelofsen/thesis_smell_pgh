# thesis_smell_pgh
Used code for Master thesis Information Studies (Data Science track)

The Jupyter notebook file contains all the code used in the project. The data importing step might need to be slightly adjusted, but the files are in the main folder of this Github.

Regarding installing packages, the following list needs to be installed:

python==3.9.0

pandas==1.1.1

matplotlib==3.3.2
numpy==1.19.4
shap==0.41.0
datetime
sklearn==0.23.2
statsmodels==0.11.1
keras==2.4.3
tensorflow==2.4.0



Important note: In order to not get an error related to tensor hashing in the feature importance step, the code below needs to be used as described in the notebook. This does result in way longer runtimes for the models.
import tensorflow as tf
tf.compat.v1.disable_v2_behavior()
