# CRYTO INVESTMENT CLUSTER ANALYSIS

As requested, in this in-depth Jupyter Lab notebook, the power of Unsupervised Machine Learning will be used to analyze crypto currency data. In this analysis, the crypto data is not only compiled, but also clustered in plots that show the relationships between all of the currencies using the K-Means clustering method and using the PCA (Principle Component Analysis) method in conjunction with the former. 

## TECHNOLOGIES

In order for this immersive application to run, there are installation requirements. They are the following:

[Python](https://www.python.org/downloads/) - Enables the user to use the powerful Python programming language.

[JupyterLab](https://jupyter.org/) - Access to the web-based IDE JupyterLab.  

[Pandas](https://pandas.pydata.org/) - Grants access to the open-source Pandas data analysis tool, which is powered by Python.

[HVPLOT](https://hvplot.holoviz.org/) - Enables the user to implement and use the interactive hvplot system to view and map data values.

[SCIKIT-LEARN](https://scikit-learn.org/stable/install.html) - Package that grants the user access to the powerful K-Means, PCA, and StandardScaler Unsupervised Learning tools.

[Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel) - Enables the user to access the source of the compiled market data for the crypto currencies.

## USAGE

In order to execute and plot this code, you must run the following:

```python
crypto_investments.ipynb
import pandas as pd
from pathlib import Path
import numpy as np
import hvplot.pandas 
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```
Download the learning kit for KMeans, PCA, and StandardScaler: `pip install -U scikit-learn`

Downloading the HoloViz hvplot package: `conda install -c pyviz hvplot`

Accessing JupyterLab in Bash: `Jupyter Lab`

## GALLERY

![image](https://github.com/MLeGare29/CRYPTO_CLUSTER_ANALYSIS/assets/127421460/5a7c79c9-b37e-43a8-9628-61904c13deb9)

![image](https://github.com/MLeGare29/CRYPTO_CLUSTER_ANALYSIS/assets/127421460/1f11feb7-d27c-4b49-a278-9b4ce1bd2a72)

![image](https://github.com/MLeGare29/CRYPTO_CLUSTER_ANALYSIS/assets/127421460/97b69918-1e48-4da9-814b-9b9e15e9a920)

![image](https://github.com/MLeGare29/CRYPTO_CLUSTER_ANALYSIS/assets/127421460/b1853e13-1938-4be7-acb1-0bfdc5002f0c)

![image](https://github.com/MLeGare29/CRYPTO_CLUSTER_ANALYSIS/assets/127421460/b781c39d-57d5-41db-9367-e692169e755b)

## CONTRIBUTORS

*Marcus LeGare (Developer)*

*Lucas Manning (Learning Assistant)*

### LICENSE

**COLUMBIA UNIVERISTY FINTECH BOOTCAMP**
