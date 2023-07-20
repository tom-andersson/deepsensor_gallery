# DeepSensor Gallery

A gallery of demonstrators, use cases, and videos to help you learn more about [DeepSensor](https://github.com/tom-andersson/deepsensor),
a Python package for modelling environmental data with neural processes (NPs).

## Set-up

To run the notebook demonstrators, first set up the Python environment with DeepSensor, PyTorch,
and Cartopy.
Note: DeepSensor can be used with TensorFlow instead of PyTorch, but PyTorch is chosen for these demonstrators.

We use [conda](https://docs.conda.io/en/latest/) to manage the environment because
it handles the third-party dependencies for Cartopy. If you don't yet have conda, you can download it
[here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html).
We also recommend using `mamba` for faster environment creation, which can be installed with
`conda install mamba -n base -c conda-forge`.

After cloning the repo, run the commands below in the root of the repository to
set up the conda environment:
- `mamba env create --file environment.yml`
- `conda activate deepsensor`

## :scroll: Demonstrators
These notebook demonstrators walk through the main functionality of DeepSensor with some example
datasets. 

| Title                                 |                                                       Content                                                       | Binder |
|:--------------------------------------|:-------------------------------------------------------------------------------------------------------------------:| :---: |
| Quick start                           |      [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/quickstart.ipynb)       | - |
| Task loader tour                      |   [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/task_loader_tour.ipynb)    | - |
| Custom plotting                       |       [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/plotting.ipynb)        | - |
| Active learning acquisition functions | [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/acquisition_functions.ipynb) | - |
| Autoregressive sampling               |      [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/ar_sampling.ipynb)      | - |
| Extending models                      |   [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/extending_models.ipynb)    | - |
| The DeepSensor interface              |       [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/interface.ipynb)       | - |
| Multi-output training                 | [:computer:](https://github.com/tom-andersson/deepsensor_demos/blob/main/demonstrators/multi_output_training.ipynb) | - |

## :scientist: Use cases
These notebooks showcase applications of DeepSensor to real-world research problems.

| Title | Content | Binder |
|:------|:-------:| :---: |
|       |   -     | - |

## :woman_student: Contributing a use case
User contributions that showcase applications of DeepSensor to real-world research problems are very welcome!
To contribute a use case notebook, please follow the instructions below:
* TODO

## :soon: :microphone: Upcoming talks
|               Date               | Title | Presenter |                                                 Register                                                  |
|:--------------------------------:|:---------------------------------------------|:----------------|:---------------------------------------------------------------------------------------------------------:|
| Friday 4th August 11am BST, 2023 | Tackling diverse environmental prediction tasks with neural processes | Tom Andersson   | [:memo:](https://digitalenvironment.org/wp-content/uploads/2023/07/20230804_CDE_Webinar_TomAndersson.pdf) |

## :microphone: Recorded talks

| Date       | Title                                        | Presenter       | Length  | Video |
|------------|:---------------------------------------------|:----------------|---------| :---: |
| April 2023 | Environmental Sensor Placement with ConvGNPs | Tom Andersson   | 15 mins | [:movie_camera:](https://youtu.be/v0pmqh09u1Y) |
| Jul 2022   | Advances in Neural Processes                 | Richard Turner  | 5 mins  | [:movie_camera:](https://www.youtube.com/watch?v=Eu6rGePXYX8) |
| May 2023   | Autoregressive Conditional Neural Processes  | Wessel Bruinsma | 1 hour  | [:movie_camera:](https://www.youtube.com/watch?v=93ZliHS0qBk) |

## :bookmark_tabs: Papers
* Tom Andersson et al. [Environmental Sensor Placement with Convolutional Gaussian Neural Processes](https://arxiv.org/abs/2211.10381). *Environmental Data Science* (2023)
* Wessel Bruinsma et al. [Autoregressive Conditional Neural Processes](https://arxiv.org/abs/2303.14468). In *Proceedings of the 11th
International Conference on Learning Representations, ICLR* (2023)
* Anna Vaugan et al. [Convolutional conditional neural processes for local climate downscaling](https://gmd.copernicus.org/articles/15/251/2022/). *Geoscientific Model Development* (2021)

## :book: Other resources
* Yann Dubois' [Neural Process Family website](https://yanndubs.github.io/Neural-Process-Family/text/Intro.html)