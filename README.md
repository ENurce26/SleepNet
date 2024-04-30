**Automated Sleep Stage Detection in Mice Using Convolutional Neural Networks**

**Description:**
This repository contains the implementation of a Convolutional Neural Network (CNN) designed to automatically detect sleep stages in mice using EEG and EMG signals. The data is processed from EDF files, with each 10-second epoch labeled as Wake, REM, or NREM sleep stages. This project aims to provide a robust tool for analyzing sleep patterns, particularly in studies related to brain health and sleep disorders.

**Why?**
The goal of this project is to develop a Custom Integrated System for High-Density Polysomnography Data Acquisition and Automated Scoring. This system is particularly focused on Assessing Sleep Disturbance After Traumatic Brain Injury, a critical area of research in neurobiology. The integration of an uplink/downlink data transfer solution enhances the efficiency of handling large-scale murine data, which is pivotal for real-time and accurate sleep stage classification.

**Quick Start**

Clone the Repository:

    git clone https://github.com/yourusername/sleep-stage-detection.git

Install Dependencies: Navigate to the project directory and install the required Python libraries:
    
    pip install -r requirements.txt

Launch Jupyter Notebook: Start Jupyter Notebook or JupyterLab in your environment. If you do not have Jupyter installed, you can install it via pip:

pip install notebook
jupyter notebook

Open the Notebook: In the Jupyter interface, navigate to the directory where the notebook is located and open the .ipynb file.

Run the Notebook: Execute the notebook cells sequentially to load data, preprocess it, build the model, and evaluate the results.

**Usage**

To use this notebook for sleep stage detection:

Open the Notebook: Launch the Jupyter Notebook or JupyterLab environment and open the provided .ipynb file.

Set the Dataset Path: Modify the edf_path variable in the notebook to point to your EEG/EMG dataset file in EDF format. Ensure the file is accessible from the directory where you are running the notebook.

Run the Cells Sequentially: Execute the cells in order, from importing libraries to loading data, preprocessing, model building, training, and evaluation.

Adjust Parameters as Needed: You may need to adjust parameters like picks for EEG and EMG channels or segment_length based on your specific dataset or analysis needs.

View the Results: Outputs including model performance metrics and any plots will be displayed directly within the notebook.

**Contributing**

Contributors are welcome to improve the accuracy and efficiency of the sleep stage detection model. Currently, the model exhibits increasing validation loss over training epochs, which may indicate a data mismatch issue. Future contributors are encouraged to investigate the pre-processing steps to ensure there is no misalignment between training and validation datasets. If you have ideas or improvements, please fork the repository, make your changes, and submit a pull request.
