**Automated Sleep Stage Detection in Mice Using Convolutional Neural Networks**

**Description:**
This repository contains the implementation of a Convolutional Neural Network (CNN) designed to automatically detect sleep stages in mice using EEG and EMG signals. The data is processed from EDF files, with each 10-second epoch labeled as Wake, REM, or NREM sleep stages. This project aims to provide a robust tool for analyzing sleep patterns, particularly in studies related to brain health and sleep disorders.

**Why?**
The goal of this project is to develop a Custom Integrated System for High-Density Polysomnography Data Acquisition and Automated Scoring. This system is particularly focused on Assessing Sleep Disturbance After Traumatic Brain Injury, a critical area of research in neurobiology. The integration of an uplink/downlink data transfer solution enhances the efficiency of handling large-scale murine data, which is pivotal for real-time and accurate sleep stage classification.

**Quick Start**

    Clone the repository:

git clone https://github.com/ENurce26/SleepNet.git

  Install required libraries:

pip install -r requirements.txt

  Run the detection script:

python detect_sleep_stages.py

**Usage**

To use this sleep stage detection system, ensure you have your dataset in an EDF file format. Place your dataset in the data directory and execute the script as shown in the Quick Start guide. The output will be a classification of each epoch into Wake, REM, or NREM stages.

python detect_sleep_stages.py --input yourdatafile.edf

**Contributing**

Contributors are welcome to improve the accuracy and efficiency of the sleep stage detection model. Currently, the model exhibits increasing validation loss over training epochs, which may indicate a data mismatch issue. Future contributors are encouraged to investigate the pre-processing steps to ensure there is no misalignment between training and validation datasets. If you have ideas or improvements, please fork the repository, make your changes, and submit a pull request.
