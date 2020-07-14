# Prediction of Dislocation Reactions

Code for Section 2 of the paper

> Sudmanns, M., Bach, J., Weygand, D., & Schulz, K. (2020). Data-driven exploration and continuum modeling of dislocation networks.
> *Modelling and Simulation in Materials Science and Engineering*.

To run the code, you would first need to obtain the data.

We use `Python 3.7.5` (in particular, out of `Anaconda3 2019.10`).
All necessary dependencies are stored in `requirements.txt`.
You can install the requirements with `pip install -r requirements.txt `.
We recommend to create a new environment before that, e.g., with `conda`, to store the specific versions of the packages.
For that environment, you can also register its own Jupyter notebook kernel as described [here](https://stackoverflow.com/questions/53004311/how-to-add-conda-environment-to-jupyter-lab).
When changing the environment, the dependency file should be re-generated: `pip freeze > requirements.txt`
