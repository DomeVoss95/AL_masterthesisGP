# Active Learning Search for pMSSM with Gaussian Processes

A Toy Model to understand the Active Learning procedure of Gaussian Processes with Batch Acquisiton.

Table of Contents

    Installation
    Usage
    Features
    Contributing
    License
    Acknowledgements

# Installation

Set up Conda environment. 
Instructions on how to install and set up the project locally. For example:

bash

Clone the repository
    git clone https://github.com/your-username/your-repository.git

Navigate to the project directory
 cd your-repository

Install dependencies
    npm install

Install environment
    conda env create --file env.yaml -n env
    

# Usage

    Use iterative_batch_selector to creates the new batch points.
    To check, wether GP works appropiatly: look at the confidence difference 
        if it's all over the place, retrain and add batch points
        if the mean is almost constant and only peaking at the points, do same


# Contributing

Guidelines for contributing to the project. For example:

    Fork the repository.
    Create a new branch (git checkout -b feature-branch).
    Make your changes.
    Commit your changes (git commit -m 'Add some feature').
    Push to the branch (git push origin feature-branch).
    Open a pull request.

# License

This project is licensed under the TUM and ATLAS License - see the LICENSE file for details.

# Acknowledgements

    Dr. Jonas Würzinger
    Prof. Dr. Lukas Heinrich
