
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/julienpaul/gitintro.git/HEAD)
[![License](https://img.shields.io/github/license/julienpaul/gitintro)](https://img.shields.io/github/license/julienpaul/gitintro)

This introduction to git is based on [coderefinery](https://coderefinery.org/) lesson [git-intro](https://coderefinery.github.io/git-intro/)

Access this Binder at the following URL

https://mybinder.org/v2/gh/julienpaul/gitintro.git/HEAD

> **Note:** see [Binder](https://mybinder.org/) to create another badge if need be

---
# Install with conda

```
conda env create -f binder/environment.yml
conda activate gitintro
```
## Configure settings
1. Run:
```
jupyter labextension disable @jupyterlab/cell-toolbar-extension
```
2. Copy the config file locally:
```
cp .jupyter/lab/user-settings/@jlab-enhanced/cell-toolbar/plugin.jupyterlab-settings ~/.jupyter/lab/user-settings/@jlab-enhanced/cell-toolbar/plugin.jupyterlab-settings
```
# Run

Once installed, launch JupyterLab with:
```
jupyter lab
```

