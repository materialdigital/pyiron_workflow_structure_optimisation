# Structure optimisation (pyiron_workflow)
This repository demonstrates structure optimisation using the `pyiron_workflow` framework. The workflow is engine-agnostic and is demonstrated here with LAMMPS.

You can fork this repository and populate it with your own data.

## Installation
Create and activate the conda environment from the provided `environment.yml`:

```bash
# Using mamba (recommended)
mamba env create -f environment.yml -n pyiron-workflow-structure-optimisation
conda activate pyiron-workflow-structure-optimisation

# Or using conda
conda env create -f environment.yml -n pyiron-workflow-structure-optimisation
conda activate pyiron-workflow-structure-optimisation

# To update an existing environment after changes to environment.yml
mamba env update -f environment.yml -n pyiron-workflow-structure-optimisation
# or
conda env update -f environment.yml -n pyiron-workflow-structure-optimisation
```

## Run the workflow
Open and execute the notebook `structure_optimisation.ipynb` in this directory:

```bash
jupyter lab
# or
jupyter notebook
```

Then open `structure_optimisation.ipynb` and run all cells.

