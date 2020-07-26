# Plagiarism Detector with AWS Sagemaker

This repository contains the files for a project on plagiarism detection. It contains the jupyter notebooks and python files of the model and training.

### Project Details

* The Dataset was preprocessed with multiple features like Longest Common Subsequence (LCS) and Containment. Based on the correlation of the features, only a couple of features were selected for the final model to be trained upon.
* The Plagiarism Detector model is built using SciKit-Learn's RandomForestClassifier.
* It was trained and deployed in AWS Sagemaker.
