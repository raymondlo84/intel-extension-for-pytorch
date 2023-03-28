# PyTorch Resnet50 Benchmarking Sample.

This sample code will run a simple inference loop to estimate the inference time for running Resnet50 on PyTorch. 

To compare the results, we added the native and also OpenVINO inference for quick time comparison with IPEX. Particularly, we will benchmark with sync and async mode to compare the performance further. 


# How to Run (Linux)


```
git clone https://github.com/raymondlo84/intel-extension-for-pytorch.git
cd intel-extension-for-pytorch
```

### Setup Virtual Environment
```
python3 -m venv ipex_openvino_env
source ipex_openvino_env/bin/activate
```
### Install OpenVINO

```
pip install --upgrade pip
pip install wheel setuptools
pip install openvino-dev[onnx]
```

### Install IPEX

```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
python -m pip install intel_extension_for_pytorch
python -m pip install intel_extension_for_pytorch -f https://developer.intel.com/ipex-whl-stable-cpu

```

### Install Jupyter Lab

```
pip install jupyterlab ipywidgets

```

### Run Jupyter Lab
```
jupyter lab examples/notebooks 
```

Then, open benchmark.ipynb and run the notebook :)


Note: https://intel.github.io/intel-extension-for-pytorch/cpu/latest/tutorials/installation.html


