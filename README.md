# ETH-global-melanoma-prediction

1. # follow this:   `https://docs.nillion.com/quickstart-install\`

Install nilup, the Nillion SDK tool installer and version manager. Binaries are available for Linux and macOS platforms
https://docs.nillion.com/quickstart-install
start a new terminal and run to check that nilup is properly installed globally
`nilup -V`

Use nilup to install the latest version of the Nillion SDK.

```
nilup install latest
nilup use latest
nilup init
```

2. # Nilion is required for the nada command! -> https://docs.nillion.com/nada
 
```
nada init melanoma_prediction
```

This will create a new directory with the project name and the following structure:
# warning on notebook then

# Update Jupyter and ipywidgets
pip install --upgrade jupyter ipywidgets
# or if you are using conda
conda install -c conda-forge jupyterlab ipywidgets

# Install Plotly
pip install plotly
# or if you are using conda
conda install -c plotly plotly
