Language Used: Python 


C:\Users\ather>python --version
Python 3.6.0
Tool Used: PyCharm

Libraries required

#Imports
import sys
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from scipy.spatial import distance as d

Code is available in code folder
Please use data.csv as data file

How to run the Code?
1.Navigate to folder where KMeans.py is available using command prompt and run the command as below. It contains 3 parameters, 1. K value 2. Data folder with file name 3. Result Folder with file name
	python KMeans.py 10 "C:/Users/ather/Desktop/data.csv" "C:/Users/ather/Desktop/result.txt"
2. Note that data.csv is indexed differently from what is given by Sir. As python uses 0 based indexing, I have renamed ID column starting from 0. Please refer data.csv. Please use data.csv for running the code.
2.Observe the plot and results in result folder
 
Please find the detailed output Brief Report.docx