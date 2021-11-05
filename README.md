# Submission(s) for the Kaggle NFL Big Data Bowl 2022

## Steps to run the Jupyter Notebooks:
1. Clone this repository: `git clone https://github.com/jon-fearer/kaggle-nfl-data-bowl-2022.git`
2. Install Python 3.8.x using your method of choice (if not installed already)
3. Change directories into the repository: `cd kaggle-nfl-data-bowl-2022`
4. Install pipenv: `python -m pip install --upgrade --user pipenv`
5. (macOS only) In order for `scipy` installation to succeed on macOS > 10, the BLAS and LAPACK libraries
are required. To install on macOS: `brew install openblas`
6. (macOS only) Set the OPENBLAS environment variable: `export OPENBLAS=$(brew --prefix openblas)`
7. Install dependencies for this project: `pipenv install`
8. Create a directory titled `input` at the root of the repository and download
the [competition data](https://www.kaggle.com/c/nfl-big-data-bowl-2022/data) from
Kaggle there. Your files should look something like this:

<p align="center">
  <img src="https://github.com/jon-fearer/kaggle-nfl-data-bowl-2022/raw/main/data-files.png">
</p>

7. Open the pipenv shell: `pipenv shell`
8. Start the Jupyter Notebook server: `jupyter notebook`
9. Navigate to the chosen notebook in your browser and click "Run" or "Run All" to
execute the code
