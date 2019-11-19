To see presentation open presentation.ipynb or presentation.pdf.<p/>

To run the notebook on you machine do the following setup:

```bash
conda create -n geo
conda activate geo
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install python=3 geopandas jupyter matplotlib descartes jupyter_contrib_nbextensions google-cloud-bigquery mplleaflet
jupyter contrib nbextension install
pip install plotly
```
<p/>
Plotly was not available with conda install.
<p/>
Thanks to the jupyter notebook extension "hide cells".<br/>
It made it possible to hide technical details during the presentation.<br/>
https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231

