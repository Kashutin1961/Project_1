HeadHunter Resume Analysis

A project for visualization and analysis of job seekers’ resumes from the HeadHunter database.
Goal — identify relationships between age, education level, work experience, and expected salary.

Project Structure

PROJECT-1/
├── Data/ # Source datasets (ignored by Git)
├── Plots/ # Saved plots (ignored by Git)
├── images/ # PNG plots for display on GitHub
├── Project-1.Notebook.ipynb # Main Jupyter analysis notebook
├── Project-1.Notebook-template.ipynb # Template for reuse
├── requirements.txt # pip dependencies
├── environment.yml # Full Conda environment specification
├── requirements_backup.txt # Backup copy of pip dependencies
├── environment_backup.yml # Backup copy of Conda environment
├── README.md # Project description
└── .gitignore # Excludes temporary and large files

Environment Setup
Via Conda (recommended)
conda env create -f environment.yml
conda activate Conda_VS_SkillsFactory_mac

Via pip
pip install -r requirements.txt


⚠️ Make sure you have Python 3.13.5 installed
📌 environment.yml includes both Conda and pip dependencies

Environment Description

Core: Python 3.13.5, Jupyter, IPython
Data Analysis: NumPy, Pandas, SciPy, Statsmodels
Visualization: Plotly, Seaborn, Matplotlib, Kaleido
Geoanalytics: GeoPandas, PyProj, Shapely, Pyogrio
Databases: psycopg2, psycopg2-binary
Web Automation: Selenium, Webdriver Manager
Utilities: dotenv, orjson, xmltodict, tqdm, tabulate
Code Quality: Ruff, Pylint, Isort

Reproducibility

All dependencies are fixed in environment.yml and requirements.txt

Plots are exported to PNG via Kaleido for display on GitHub

.gitignore is used to exclude temporary and large files

It is recommended to run notebooks in the Conda environment to avoid conflicts

Running the Project

After activating the environment, launch Jupyter:

jupyter lab

Recommendations for Improvement

Add README_en.md for English-speaking users

Include an example of running the notebook with sample plots

Add badge statuses (Python version, environment health)

In the future — containerization via Docker for full portability

Feedback

If you find a bug or want to suggest an improvement — create an issue or pull request. The project is open for development and enhancement.
