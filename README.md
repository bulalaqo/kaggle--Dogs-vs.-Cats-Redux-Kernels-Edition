# DogVsCat

##dataset
https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data


## Requirements

* Python3.5
* Anaconda
* tensorflow-gpu
* keras
* opencv 
* numpy 
* pandas 
* jupyter notebook 
* matplotlib 
* cython
* pillow
* pydot
* graphviz

## Install


```
wget https://repo.anaconda.com/archive/Anaconda2-5.2.0-Linux-x86_64.sh
bash Anaconda2-5.2.0-Linux-x86_64.sh
source .bashrc
conda create -n cv python=3.5
conda install --channel https://conda.anaconda.org/anaconda tensorflow-gpu
git clone https://github.com/fchollet/keras.git
cd keras/
python setup.py install
conda install opencv 
conda install numpy pandas jupyter notebook matplotlib cython
pip install pillow
pip install pydot
sudo apt-get install graphviz

```

## Usage
First

```
jupyter notebook --generate-config
jupyter notebook password
vim ~/.jupyter/jupyter_notebook_config.py

> c.NotebookApp.ip='*'
```

Second, start. 

```
nohup jupyter notebook DogVsCat.ipynb >> log.txt 2>&1 &
```

##kaggle score
0.03974 (15/1314)

## Author

https://github.com/JasonZhou89
