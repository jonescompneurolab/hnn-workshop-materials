[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jonescompneurolab/hnn-workshop-materials/HEAD)

# HNN workshop materials

Here we provide HNN-core notebooks that compliment the following
[HNN-GUI tutorials](https://hnn.brown.edu/tutorials/):
 * Alpha/Beta tutorial
 * ERP tutorial

# SfN 2023 Workshop Instructions
### Loading HNN-GUI
Copy and paste the following into the terminal of the virtual desktop:
```
singularity pull docker://jonescompneurolab/hnn
singularity shell hnn_latest.sif
source /home/hnn_user/hnn_envs
cd /home/hnn_user/hnn_source_code
python3 hnn.py
```

### Loading hnn-core jupyter notebook
Copy and paste the following into the terminal of the virtual desktop:
```
module load hnn-workshop/2023.11
module load miniconda/4.12.0 firefox/87.0
source /oscar/runtime/opt/hnn-workshop/2023.11/bin/activate
git clone https://github.com/jonescompneurolab/hnn-workshop-materials
cd hnn-workshop-materials/ 
jupyter notebook
```
