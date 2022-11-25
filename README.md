# Modified-RootNav
This is the modified version of [RootNav 2.0 Code repository](https://github.com/robail-yasrab/RootNav-2.0). 
Original [RootNav-2.0](https://github.com/robail-yasrab/RootNav-2.0) algorithm works on encoder based CNN for plant skeleton detection, 
whereas this repository is based on Mask-RCNN for image segementation and skeleton extraction for further analysis of plant phenotype property study.


## Installation
You will first need to download the code, either as a zip above, or by cloning the git repository (recommended):
```
git clone https://github.com/Kamlesh364/Modified-RootNav2.0/
```
Next, install the required dependencies. If you're using pip, then the following will work in Linux:
```
cd Modified-RootNav2.0
pip install -r requirements.txt
```

This will download and set up all the required libraries, providing you with a Python(>=3.6) installation.

## Using the tool
This repository can only be used `training` and will be availble for `inference` shortly.

### Training new models
Training code may be found in the `training` folder. Instructions on training models are given in the [training README](https://github.com/Kamlesh364/Modified-RootNav2.0/tree/main/training).

## References
<a id="1">[1]</a> 
Yasrab, R., Atkinson, J. A., Wells, D. M., French, A. P., Pridmore, T. P., & Pound, M. P. (2019), 
RootNav 2.0: Deep learning for automatic navigation of complex plant root architectures, 
GigaScience, 8(11), giz123.

<a id="2">[2]</a> 
He, Kaiming. “Mask R-CNN.” arXiv.org, 20 Mar. 2017, arxiv.org/abs/1703.06870.
