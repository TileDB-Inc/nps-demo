# nps-demo
NPS Contract Python Lidar Demo

## Setup

You need to install [Conda](https://conda.io/docs/) to install the environment / dependencies to run the demo.

```
git clone https://github.com/TileDB-Inc/nps-demo
cd nps-demo
conda env create -f environment.yaml --force
```

## Run Demo Notebook

To run the notebook, activate the installed Conda environment:

```
source activate nps-demo
jupyter notebook tiledb-lidar.ipynb
```

After exiting the notebook interface, deactivate the Conda environment with:

```
source deactivate nps-demo
```
