Model downloads are divided into initial downloads and updates to the model directory. Please refer to the corresponding documentation for instructions on how to proceed.


# Initial download of model files

### Download the Model from Hugging Face

Use a Python Script to Download Model Files from Hugging Face
```bash
pip install huggingface_hub
wget https://github.com/opendatalab/MinerU/raw/master/scripts/download_models_hf.py -O download_models_hf.py
python download_models_hf.py
```
The Python script will automatically download the model files and configure the model directory in the configuration file.

The configuration file can be found in the user directory, with the filename `magic-pdf.json`.


# How to update models previously downloaded

## 1. Models downloaded via Hugging Face or Model Scope

If you previously downloaded models via Hugging Face or Model Scope, you can rerun the Python script used for the initial download. This will automatically update the model directory to the latest version.
