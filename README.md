# vispaths

![OS](https://img.shields.io/badge/OS-independent-green)
![Python](https://img.shields.io/badge/python-3.10-blue)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Dataset](https://img.shields.io/badge/dataset-Zenodo-4A90E2)](https://doi.org/10.5281/zenodo.19497525)


Analysis for the visual pathways project

You need to install the piepy package first:

```pip install piepy-neuro```

After that you can navigate into `notebooks\manuscript\fig*\` to run notebooks to create panels from the manuscript.

> **IMPORTANT:**
> 
>Piepy creates a `.piepy\config.json` directory in your home directory and fills it with default values. Inside the `config.json` there is a `path` variable which includes all the paths piepy looks at for raw beahvioral/imaging data.

For running the notebooks in this repository, you do not need to modiify this file, as a preprocessed `manuscript\260410_Ncomm_inhibition_data.parquet` file already exists inside the repository.

To be able to regenerate training related fiures (Fig. 1 and Fig. 2), you need to use the training datasets published in [zenodo](https://doi.org/10.5281/zenodo.19497525).

## Contact

Sakir Kaan Cetindag cetindag.kaan@gmail.com
