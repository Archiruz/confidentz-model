# confidentz-model
This is a repository for dataset and machine learning model versioning of ConfiDentz Project. Confidentz model is a part of our ConfiDentz project. This model was trained using 500 images of healthy and caries tooth images. This document will guide you to train your own model.

# Pre-requisites
* VSCode / any text editor
* Git
* Conda
* DVC (Data Version Control)

# Installation

## Windows
1. Clone the repository with:
    ```bash
    git clone https://github.com/Confidentz-C23-PS334/confidentz-model
    ```
    
2. Enter the directory

3. Get the dataset by running:
    ```bash
    dvc get https://github.com/Confidentz-C23-PS334/confidentz-model dataset.zip
    ``` 
    
4. Create conda environment by running:
    ```bash
    conda env create -n ENVNAME --file environment.yml
    ``` 
    Change ENVNAME to your preferred environment name
    
5. Open ``train.ipynb`` with VSCode or other to start training model

# How to train your model
1. Connect to Jupyter notebook server and use the environment name you have defined as the kernel
2. Run through every cells in ``train.ipynb``
3. Export the model as ``.h5`` format

# Machine Learning Team
|Name  | StudentID  | University | links |
|--|--|--|--|
| Alvian Rahmadani Saputra | M282DKX3756 | Universitas Negeri Malang |[Github](https://github.com/archiruz)|
| Fahmi Zulkarnain Habib | M282DSX0429 | Universitas Negeri Malang |[Github](https://github.com/zulkou)|

# Links
Link to dataset: [Google Drive](https://drive.google.com/drive/folders/1nwR-wo-_9mQtqkVJd3Grhlw6YGPX4EKP?usp=drive_link)
