## CE9010: Introduction to Data Science <br> Semester 2 2017/18 <br> Xavier Bresson <br>
  
  
## Install Python 

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

   Note: Instructions based on Michael Defferrard, December 2017<br>
   Note: Read [Conda command lines for packages and environments]

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf


## Run Python notebooks 

First time:

1. Open a terminal. Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Download the Python notebooks: Go to folder CE9010_2018 with `cd CE9010_2018`, and `git pull`. 
1. Activate the environment with `activate CE9010_2018`
   (or `conda activate CE9010_2018`, or `source activate CE9010_2018`).
1. Start Jupyter with `jupyter notebook` (or `jupyter-notebook`, or `jupyter lab`). The command
   opens a new tab in your web browser.
1. Go to the folder `tutorials` and duplicate the notebook `tutorial01.ipynb` (for example) with the new name `my_tutorial01.ipynb` (to avoid future conflicts).
1. Open, edit and run the notebook `tutorial01.ipynb` from your browser.
1. When you are done with the notebook, go back to the terminal and shut down the juypter kernels with `Control-C`. 
1. Save the notebook with git: `git branch my_branch`, `git checkout my_branch`, `git add .`, and `git commit -m tutorial01`.

	Note for Windows: Folder CE9010_2018 is located at `C:\Users\user_name\CE9010_2018`<br>
	Note: Common Conda commands are: `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
   Note: Add a python library to the environment: `conda install -n CE9010_2018 numpy` (for example)<br>
   Note: Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf


<br>
The following times:

1. Open a terminal. Windows: Open the Anaconda Prompt terminal from the Start menu.
1. Go to folder CE9010_2018 with `cd CE9010_2018`, and `git checkout master`, `git pull`, `git checkout my_branch`, and `git merge master`.
1. Activate the environment with `activate CE9010_2018`
   (or `conda activate CE9010_2018`, or `source activate CE9010_2018`).
1. Start Jupyter with `jupyter notebook` (or `jupyter-notebook`, or `jupyter lab`). The command
   opens a new tab in your web browser.
1. Go to the folder `tutorials` and duplicate the notebook `tutorial02.ipynb` (for example) with the new name `my_tutorial02.ipynb`.
1. Open, edit and run the notebook `tutorial02.ipynb` from your browser.
1. When you are done with the notebook, go back to the terminal and shut down the juypter kernels with `Control-C`. 
1. Save the notebook with git: `git add .` and `git commit -m tutorial02`.

   Note: [git commands]<br>
   Note: [Understanding git conflicts]

[git commands]: git/git_commands.pdf
[Understanding git conflicts]: git/git_xb.pdf




[git]: https://git-scm.com
[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org


<br>
<br>
<br>

