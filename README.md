# Network Distruption

This project has been developed to distrupt complex networks.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project has been developed to distrupt complex networks.
	
## Technologies
Project is created with:
* Python version: 3.7.3

With the following libraries:
* NetworkX library version: 2.3
* Numpy library version: 1.16.4
* Pandas library version: 0.25.1

Additional libraries (to plot the results):
* Matplotlib library version: 3.1.1
* Seaborn library version: 0.9.0
	
## Setup
To run this project, run network-disruption.py. 
```
$ python network-disruption.py
```

* The main automatically will import the datasets from the "Datasets" folder, and will store the results obtained in the related sub-folder of the "Results" one.

To plot the results, run network-disruption-plots. 
```
$ python network-disruption-plots.py
```

* The main automatically will import the input DataFrame from the appropriate "Results" sub-folder, and will store the plots obtained in the related sub-folder of the "Results" one.
