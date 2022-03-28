# URBA6004 Tutorial - OSMnx

## Summary

In this tutorial, you will:

- Extract street network from OSM using: 1. A place name and 2. custom polygon
- Map the street network
- Analyse the street network
- Save the network as Shapefile, GeoPackage, SVG

In the end of this tutorial, you will be able to replicate the map below:

TODO: Add image

## Background - What is OSMnx?

OSMnx is a Python package for following uses:

- extract and save street network data from OpenStreetMap
- visualise street network
- analyse and visualise the street network data using different measures


## Usage - How to use the notebook?

### Using JupyterLab

The **bigdata** environment created in the first tutorial will be used. 

1. Open Anaconda Prompt (Windows) or Terminal (Mac)

1. Switch to the **bigdata** conda environment

   ```sh
   conda activate bigdata
   ```

2. Install the `osmnx` package

   ```
   conda install osmnx
   ```

3. Start JupyterLab

   ```
   jupyter lab
   ```

4. Navigate to the notebook and start conducting the analysis



### Using Colab

If you are using Colab for this notebook, you will need to install osmnx via pip:

```
pip install osmnx
```

Colab will return an error message, this is expected behaviour. You will need to restart the kernel.

After that, check whether osmnx can be imported with the following code

```python
import osmnx as ox

osmnx.__version__
```



