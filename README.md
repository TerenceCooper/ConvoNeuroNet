# ConvoNeuroNet
The required packages and libraries are all in terence_env.yml  
My own enviroment:  
   OS: GNU/Linux 3.16.0-4-amd64 x86_64 Debian.jessie  
   python version: anaconda 1.4.0  
   	  	   python 2.7.12  
## Download The Dataset  
   [The Street View House Numbers (SVHN) Dataset](http://ufldl.stanford.edu/housenumbers)  
   
## Set Up Enviroment  
   Make sure you have installed [anaconda](https://docs.continuum.io/anaconda/install#linux-install)
   1. Create a local enviroment as mine:  
      `conda env create -f terence_env.yml`
   
   2. Activate the enviroment(whose name is 'tensorflow'):  
      `source activate tensorflow`
      
## Run the jupyter notebook  
   `jupyter notebook data_preprocess.ipynb`

## This is my current directory tree if it helps:  
.  
├── conv_net.ipynb  
├── convonet_model.mdl  
├── convonet_model.mdl.meta  
├── data_preprocess.ipynb  
├── extra/  
├── extra.tar.gz  
├── project_report.pdf  
├── README.md  
├── summaries  
├── SVHN.pickle  
├── terence_env.yml  
├── test/  
├── test.pickle  
├── test.tar.gz  
├── toy_data.pickle  
├── train/  
├── train.tar.gz  
└── valid.pickle

