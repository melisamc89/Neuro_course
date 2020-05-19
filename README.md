# Assignment 4 -- instructions and structure

For this assignment you will need to create a new environmnet called Caiman containing all relevant libraries for source extraction.
Installationthrough conda-forge (August 2019) can be found here[CaImAn](https://github.com/flatironinstitute/CaImAn/blob/master/docs/source/Installation.rst)



Before starting the assignment remember to activate caiman environment by doing conda activate caiman.


In this assignment you will work with multiple files. It is recommendable to separate those files according to the step of processing they belong to.

Assignment4
│
│──assignment4.ipynb        <- File contaning explanations and exercises for calcium imaging analysis assignment
│──auxiliary_functions.py   <- File contaning some plotting fuctions that are used in the notebook
│──normalization_functions.py   <- File contaning functions for normalizarion of temporal traces
│
├──data                <- Folder containing all relevant data, and where produced files will be saved
│   ├── raw            <- raw data provided
│   │
│   ├── source_extrated  <- source extracted data provided for MultipleSession analysis.
│   │
│   ├── motion_corrected <- folder to save motion corrected files
│   │
│   ├── traces          <- calcium temporal traces provided to perform basic analysis
│
├──figures              <- Folder for saving generated figures




