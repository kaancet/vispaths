# vispaths

![OS](https://img.shields.io/badge/OS-independent-green)
![Python](https://img.shields.io/badge/python-3.10-blue)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Dataset](https://img.shields.io/badge/dataset-Zenodo-4A90E2)](https://doi.org/10.5281/zenodo.19497525)


Analysis for the visual pathways project

It is recommended to use [uv](https://docs.astral.sh/uv/getting-started/installation/) for package and environment management and any IDE to run the notebooks (recommended [vscode](https://code.visualstudio.com/download)).

You can clone this repository to a desired location and from a terminal navigate into it. Then run:

```uv venv --python 3.10```

After which you can activate the environment by:

Linux\MacOs:
```source .venv\bin\activate```

Windows:
```.venv\Scripts\activate```

Once the environment is activated you need to install the piepy package:

```uv pip install piepy-neuro```

After that you can navigate into `notebooks\manuscript\fig*\` to run notebooks to create panels from the manuscript. Running each cell in the notebooks by order will generate the panel in the manuscript designated by the file name, e.g. `3.E_V1_reaction_time_change.ipynb`


> **IMPORTANT:**
> 
>Piepy creates a `.piepy\config.json` directory in your home directory and fills it with default values. Inside the `config.json` there is a `path` variable which includes all the paths piepy looks at for raw beahvioral/imaging data.

For running the notebooks in this repository, you do not need to modify this file, as a preprocessed `manuscript\260410_Ncomm_inhibition_data.parquet` file already exists inside the repository.

To be able to regenerate training related fiures (Fig. 1 and Fig. 2), you need to use the training datasets published in [zenodo](https://doi.org/10.5281/zenodo.19497525).

## Contact

Sakir Kaan Cetindag cetindag.kaan@gmail.com
