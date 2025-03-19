This code will generate a txt with a summary report of the csv file and a png highlighting the outliers.
The txt file contains the total energy usage, daily average usage and the numbers of outliers detected
In this version the csv file needs to have two columns named 'energy_usage' and 'date'.
It uses Z-score to calculate outliers

Libraries needed: 
  - Pandas
  - Numpy
  - Matplotlib.pyplot
