## Introduction
This code uses the TEP dataset to analyze and visualize the Fault-Free and Faulty data. The main objective is to detect any anomalies in the data using basic statistical analysis. If any variable goes out of the pre-defined limit, then the code generates an error.


## Installation

To run the code, the following steps can be followed:

1. Clone the repository using git clone https://github.com/<username>/<repository-name>.git
2. Install the required packages using pip install -r requirements.txt
3. Run the code using python <filename>.py
    
## Requirements

- Python 3
- pyreadr
- matplotlib
- seaborn
- numpy
- pandas


## Usage/Examples

The code reads the TEP dataset which is in R format. It uses the pyreadr library to read the R-files. The matplotlib and seaborn libraries are used for data visualization. The numpy and pandas libraries are used for basic statistical analysis.

The code can be run in a Jupyter Notebook or from the command line using the Python interpreter.


## Acknowledgements

 - [The TEP Dataset](https://www.kaggle.com/datasets/averkij/tennessee-eastman-process-simulation-dataset)
 - [Blog Post on TEP process](https://keepfloyding.github.io/posts/data-explor-TEP-3/)


