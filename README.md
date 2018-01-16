

## CE9010: "Introduction to Data Science"
## Sem 2 2017-18
## Xavier Bresson


<br>
## Install Python  
<br>



For a local installation, [Python] and [git] are needed. It is recommended to install [Miniconda], a distribution of the [conda] package and environment manager. Please follow the below instructions to install it and create an environment for the course:

1. Download the Python 3.6 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
   * Windows: Double-click on the `Miniconda3-latest-MacOSX-x86_64.exe` file. 
   * macOS: Run `bash Miniconda3-latest-MacOSX-x86_64.sh` in your terminal.
   * Linux: Run `bash Miniconda3-latest-Linux-x86_64.sh` in your terminal.
1. Open a terminal. Note for Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Install git by typing: `conda install git`.
1. Download the Python repository of the course by running
   `git clone https://github.com/xbresson/CE9010_2018`.
1. Create an environment with the packages required for the course with
   `conda env create -f CE9010_2018/environment.yml`. Note 1: It may take some time. Note 2: List the python packages with `conda list`.




<br>
## Run Python codes  
<br>

1. Open a terminal. Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Activate the environment with `activate CE9010_2018`
   (or `conda activate CE9010_2018`, or `source activate CE9010_2018`).
1. Start Jupyter with `jupyter notebook` (or `jupyter-notebook`, or `jupyter lab`). The command
   opens a new tab in your web browser.
1. Edit and run the notebooks from your browser.



<br>
Note: Instructions based on Michael Defferrard, December 2017


[git]: https://git-scm.com
[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org
