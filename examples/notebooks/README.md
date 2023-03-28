# How to Run (Linux)

### Setup Virtual Environment
```
python3 -v venv ipex_openvino_env
source ipex_openvino_env
```
### Install OpenVINO

```
pip install --upgrade pip
pip install wheel setuptools
pip install openvino-dev 
```

### Install IPEX

```
pip install intel_extension_for_pytorch
pip install intel_extension_for_pytorch -f https://developer.intel.com/ipex-whl-stable-cpu

```

### Install Jupyter Lab

```
pip install jupyterlab

```

### Run Jupyter Lab
```
jupyter lab .
```

Then, run the notebook :)
