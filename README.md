# Naive Bayes Bag of Words Classifier

This repository contains a Jupyter Notebook that implements an NB BoW classifier over the 20 newsgroups text dataset. The notebook does not require any external dependenices or package installations beyond the default Python installation.

## Requirements

* Python 3.8+
* Jupyter Notebook

## Running the Notebook

1. Open the Jupyter Notebook

    From inside this projects directory

    ```cmd
    jupyter notebook
    ```

    Then open the `.ipynb` file in your browser.

2. Run all cells
In the Jupyter menu bar, click **Kernel → Restart and Run All**.

## Notes

You do not need to unzip the 20 newsgroups dataset. I implemented an extraction method to created a temporary directory for the dataset at the beginning of execution, and then it is removed upon termination.