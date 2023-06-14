# confidentz-model
Repository for dataset and model versioning of ConfiDentz Project.

# Pre-requisites
* VSCode / any text editor
* Git
* Conda
* DVC (Data Version Control)

# Installation

## Windows
1. Clone the repository with:  
``git clone https://github.com/Confidentz-C23-PS334/confidentz-model``
2. Enter the directory
3. Get the dataset by running:  
``dvc get https://github.com/Confidentz-C23-PS334/confidentz-model dataset.zip`` 
4. Create conda environment by running:  
``conda env create -n <ENVNAME> --file environment.yml`` 
5. Open ``train.ipynb`` to start training model

# How to train your model
1. Just run through every cells in ``train.ipynb``
2. Export the model as ``.h5`` format

Link to dataset: [Google Drive](https://drive.google.com/drive/folders/1nwR-wo-_9mQtqkVJd3Grhlw6YGPX4EKP?usp=drive_link)
