# PyTorch Resnet50 Benchmarking Sample.

This sample code will run a simple inference loop to estimate the inference time for running Resnet50 on PyTorch. 

To compare the results, we added the native and also OpenVINO inference for quick time comparison with IPEX. Particularly, we will benchmark with sync and async mode to compare the performance further. 


# How to Run (Linux)

### Setup Virtual Environment
```
python3 -m venv ipex_openvino_env
source ipex_openvino_env/bin/activate
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
jupyter lab examples/notebooks 
```

Then, open benchmark.ipynb and run the notebook :)

