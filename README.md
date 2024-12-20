# TSO-FS25
Traffic System Operations, spring semester 2025

<a target="_blank" href="https://colab.research.google.com/github/ZHAW-ZAV/TSO-FS25">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## How to work
You have two options to work in this course: with a local installation of the conda/mamba environment or with Google Colab.

### Local installation
1. In a command line, navigate to the folder where you want to keep this repository and clone it.
   ```bash
    cd path/to/your/folder
    git clone https://github.zhaw.ch/TraffSysOps/FS25.git
    ```
2. Install Miniforge by following the instructions [here](https://github.com/conda-forge/miniforge).
3. Create the environment by running the following command in the terminal:
   ```bash
   mamba env create -f environment.yml
   ```

You can activate the environment with the following command to use it in your terminal:
```bash
conda activate tso-fs25
```
You can also use your favorite IDE to work with the environment. We recommend using [Visual Studio Code](https://code.visualstudio.com/) with the Python and Jupyter extensions. There is plenty of documentation on how to set up your environment with these tools and on the internet.

If you want to update your local copy of this repository, you can do so by running the following command in the terminal:
```bash
cd path/to/your/folder/FS25
git pull
```

If you want to update your environment, you can do so by running the following command in the terminal:
```bash
mamba env update -f environment.yml
```

### Google Colab
1. Click on the `Open in Colab` badge at the top of this README.md file.
2. Follow the instructions in the notebook to clone the repository and set up the environment.

