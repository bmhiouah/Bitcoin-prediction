# Case study ST4 MDS
This repo contains all starting files for ST4 MDS case study

# Fork this repository
Fork this repository so that you can commit your changes

## Installation

* Go to path

`cd /path/to/st4_mds_prepa`

* Create a virtual environment (you may skip this step if mds_env already exists in your directory)

**Using virtualenv**

`virtualenv -p python3 mds_env`

**Using conda**

`conda create -n mds_env python=3`

* Activate virtual environment

**Using virtualenv**

`. mds_env/bin/activate`

**Using conda**

`source activate mds_env`

* Install requirements

`pip install -r requirements.txt`


## Project Organization

    ├── README.md          <- Contains desctiption of the project
    ├── notebook           <- folder for notebook
        ├── case_study_group_n.ipynb <- starter notebook for case study, replace n by the group number
    ├── data               <- folder for data
        ├── df_blockchain.csv <- bitcoin and blockchain data from https://blockchain.info/
    ├── .gitignore
