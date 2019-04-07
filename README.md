-----------------------------
### Time serires clustering and classification
-----------------------------

This folder contains a previous work (https://arxiv.org/abs/1802.01059) which 
has been very succesful in time series clustering. 

The aim of this repo is to fine tune this model for clustering of medical data. The medical data consist of acoustic emission data used for monitoring knees.  The clustering would help us understand the degree of wear occuring on the artificial knee surfaces

On the other hand it is desirable to be able to classify to collected signals based on the wear on the surface. This has huge benefit because it could help in the diagnosis of wear that occur on artificial knees. 

To achieve the classification of the wear, the approach that would be used here would be to convert time series into graham matrix and feed this into neural net

# dtc-tensorlow
This repository for [「Deep Temporal Clustering: Fully Unsupervised Learning of Time-Domain Features」](https://arxiv.org/abs/1802.01059).  
We use synthetic dataset (a superposition of sinusoids).  
please let me know if you have any questions to email: saeeeeru29@gmail.com

## Usage
## requirements
- Written for Python3.x
- Please check required Python Library in ./requirements.txt

## Installation
1. Install required Python Library

~~~
pip install -r ./requirements.txt
~~~

### Run demo
1. Learn Deep Temporal Clustering Model

	```
	sh demo.sh
	```

2. Inference clustering results of learnd Model

	```
	python inference.py
	```
