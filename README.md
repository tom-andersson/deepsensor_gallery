# DeepSensor Demonstrators

The repository contains tutorials and demonstrators for [DeepSensor](https://github.com/tom-andersson/deepsensor),
a Python package and open-source project for modelling environmental data with neural processes (NPs).

## Set-up:

To run the notebook demonstrators, first set up the Python environment with DeepSensor, PyTorch,
and Cartopy. We use [conda](https://docs.conda.io/en/latest/) to manage the environment because
it handles the third-party dependencies for Cartopy. 
If you don't yet have conda, you can download it
[here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html).

After cloning the repo, run the commands below in the root of the repository to
set up the conda environment:

- If you don't have [mamba](https://github.com/mamba-org/mamba) already, install
it to your `base` env for faster conda operations: `conda install -n base mamba -c
conda-forge`. If you don't want to install mamba, you can use `conda` in the commands below instead.
- `mamba env create --file environment.yml`
- `conda activate deepsensor`

## DeepSensor tutorials:
| Title       |                                               Content                                                | Binder |
|:------------|:----------------------------------------------------------------------------------------------------:| :---: |
| Quick start | [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/tutorials/quickstart.ipynb) | - |

## DeepSensor demonstrators:
| Title | Content | Binder |
|:------|:-------:| :---: |
|       |   -     | - |

## Contribute:

If you want to contribute a demonstrator, please follow the instructions below.

### Add a new demonstrator:
TODO