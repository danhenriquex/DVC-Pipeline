<h1 align="center">🚗 AI Project Managment</h1>
<p align="center" id="objetivo">Learning Hydra and DVC integration for Machine Learning projects.</p>

<p align="center">🚀 This project demonstrates a full machine learning pipeline using DVC (Data Version Control), Hydra, and Python. The pipeline includes data preparation, feature engineering, model training, and evaluation.

</p>

<p align="center">
 <a href="#overview">Overview</a> •
 <a href="#features">Technologies and Tools Used</a> •
 <a href="#roadmap">Project Structure</a> • 
 <a href="#tecnologias">Getting Started</a> • 
 <a href="#author">Running the Pipeline</a>
<a href="#author">What I Learned</a>
</p>

<h4 align="center"> 
	🚧  Machine Learning Project 🚀 Finished  🚧
</h4>

### Overview

<div style='margin: 20px' id="overview">
 This project aims to showcase the use of DVC and Hydra in managing a machine learning pipeline. The project is organized into modular Python scripts, each responsible for a specific part of the pipeline. The main goal is to create a reproducible and scalable workflow for machine learning experiments.
</div>

### Features

<div id="features">

- Python: The programming language used for the entire pipeline.
- DVC (Data Version Control): Used for tracking data, models, and experiments.
- Hydra: A configuration management framework that simplifies the handling of multiple configuration files and command-line arguments.
- PyTorch: Used for building and training the machine learning model (if applicable).
- Scikit-learn: Used for data preparation and feature engineering (if applicable).
- Pandas: For data manipulation and analysis.
- Git: For version control.
- Google Drive: Used as a remote storage for DVC (optional).
- Datasets: MNIST and CIFAR10

</div>

<div id="roadmap">

### Project Structure

.
├── prepare_data.py          # Script to prepare and clean the data

├── train.py                 # Script to train the machine learning model

├── make_features.py         # Script to create features from the raw data

├── evaluate.py              # Script to evaluate the trained model

├── dvc.yaml                 # DVC pipeline configuration

├── .dvc/                    # DVC metadata directory

├── .gitignore               # Git ignore file

├── README.md                # Project documentation (this file)

└── data/                    # Directory containing the data (managed by DVC)


### Scripts Overview

- prepare_data.py: Handles data loading, cleaning, and preprocessing.
- make_features.py: Extracts features from the preprocessed data and saves them for model training.
- train.py: Trains the machine learning model using the prepared features.
- evaluate.py: Evaluates the trained model on a test set and reports the performance.

### What I learned

	
- DVC: How to use DVC to version control data, track experiments, and manage model files.
- Hydra: How to use Hydra to manage configuration files and command-line arguments, making the project more flexible and easier to scale.
- Pipeline Structuring: The importance of organizing a machine learning project into modular scripts to create a clear and maintainable workflow.
- Reproducibility: Ensuring that experiments are reproducible by tracking data, code, and configurations.

</div>


### Author

---

<!-- <script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script> -->

<div align="left" id="author">

<a href="https://github.com/danhenriquex">
  <img src="https://github.com/danhenriquex.png" width="100" height="100" style="border-radius: 50%"/>
</a>

<!-- <div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="pt_BR" data-type="vertical" data-theme="dark" data-vanity="danilo-henrique-santana"><a class="LI-simple-link" href='https://br.linkedin.com/in/danilo-henrique-santana?trk=profile-badge'>Danilo Henrique</a></div> -->
</div>

<div style="margin-top: 20px" >
  <a href="https://www.linkedin.com/in/danilo-henrique-480032167/">
    <img  src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</div>
