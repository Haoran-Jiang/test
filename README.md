# [Deep Hidden Physics Models]

This repository explores the techniques develpoed in:

>[Deep Hidden Physics Models: Deep Learning of Nonlinear Partial Differential Equations](https://arxiv.org/abs/1801.06637)
Raissi, Maziar.

For more information, please refer to the following: (https://maziarraissi.github.io/DeepHPMs/)

# Installation

Installation is most easily done using pip.
1. Create or activate a virtual environment (e.g. using `virtualenv` or `conda`).
2. [Install TensorFlow](https://www.tensorflow.org/install/pip)
3. Install required packages
```bash
cd <your directory>
pip freeze > requirements.txt
```

For Chebfun package in MATLAB, we can install it to your current directory by pasting the code below to your MATLAB command
window
```MATLAB
unzip('https://github.com/chebfun/chebfun/archive/master.zip')
movefile('chebfun-master', 'chebfun'), addpath(fullfile(cd,'chebfun')), savepath
```