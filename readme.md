conda create -n geo
conda activate geo
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install python=3 geopandas jupyter matplotlib descartes jupyter_contrib_nbextensions google-cloud-bigquery mplleaflet

# Takk https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231
jupyter contrib nbextension install 
