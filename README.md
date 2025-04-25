# Turn_sequence_chemotaxis

This repository contains the data and code used to generate the figures for the paper.

## Data

All necessary data files for reproducing the figures are located in the `Data` directory. Large data files within this directory are managed using **Git Large File Storage (LFS)**.

**Important:** To ensure proper access to these large data files, please follow the instructions below *before* running the code.

### Git LFS Installation and Setup

1.  **Install Git LFS:**
    If you don't have Git LFS installed, please install it. You can find installation instructions for your operating system on the [Git LFS website](https://git-lfs.com/). For example, on macOS using Homebrew, you can use:
    ```bash
    brew install git-lfs
    ```

2.  **Initialize Git LFS for this repository:**
    After installing Git LFS, navigate to the root directory of this repository in your terminal and run:
    ```bash
    git lfs install
    ```

3.  **Download the tracked files:**
    To download the large data files managed by LFS, run the following command in the repository's root directory:
    ```bash
    git lfs pull
    ```

## Code

The primary code file for generating the figures is:

-   `All_codes_for_figures_250425.ipynb`

This Jupyter Notebook contains all the necessary code to reproduce the figures presented in the paper.


## Running the Code

The `All_codes_for_figures_250425.ipynb` Jupyter Notebook can be readily executed using Google Colaboratory, a free online Jupyter Notebook environment that requires no setup.

1.  **Open in Colaboratory:** Click on the following badge to open the notebook directly in Google Colaboratory:

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/KarinSuwazono/Turn_sequence_chemotaxis/blob/main/Codes/All_codes_for_figures_250425.ipynb)

2.  **Data Access:** Follow the instructions in the [Usage in Google Colaboratory](#usage-in-google-colaboratory) section to clone the repository and pull the necessary data files (including those managed by Git LFS) into the Colaboratory environment.

3.  **Execute Cells:** Once the data is accessible, you can execute the cells in the notebook to reproduce the figures.


4.  **Output:**
    **The generated figures will be saved in the `/content/Figures/` directory within the Colaboratory environment.**


## Dependencies

All necessary Python libraries and software dependencies are imported within the `All_codes_for_figures_250425.ipynb` notebook. Please refer to the import statements at the beginning of the notebook for a complete list of required packages.

If you encounter any `ModuleNotFoundError` in Google Colaboratory, it indicates that a required library is not installed in the environment. You can typically install missing libraries using `pip` within the Colaboratory notebook itself. For example:

```python
!pip install missing_library_name
