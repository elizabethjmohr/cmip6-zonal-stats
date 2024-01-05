# Zonal Stats Demo using xagg

This repo contains a Jupyter notebook that calculates average surface temperature for each county in the United States according to a CMIP6 model.

It also contains an environment.yml file with necessary dependencies. You can create a conda environment by running this on the command line:

```
conda env create -f environment.yml
```

To use this environment in a Jupyter Notebook, first activate it:

```
conda activate zonal_stats
```

Next, create a kernel for the environment:

```
python -m ipykernel install --user --name=zonal_stats
```

Finally, launch the notebook:

```
jupyter notebook
```
