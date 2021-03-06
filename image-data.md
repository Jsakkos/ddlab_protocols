# Microscopy image data storage with OMERO

OMERO is an image repository for organizing, analyzing, and sharing image data

## Getting started

### Create an account

1. Go to the [signup page](http://35.8.197.106/signup/) and create an account.
   - If you are connected to the MSU network, enter your login and password to connect.
   - If you are not connected to the MSU network, first connect via [VPN](https://new.vpn.msu.edu) before attempting to login.

### Importing data

1. Download and install the OMERO.insight desktop client [here](https://www.openmicroscopy.org/omero/downloads/)

1. Add the server address (35.8.197.106) to the list of servers by clicking on the wrench icon.
   - If you are connected to the MSU network, enter your login and password to connect.
   - If you are not connected to the MSU network, first connect via [VPN](https://new.vpn.msu.edu) before attempting to login.
1. Select the Import Data button, add the desired files or folders to the import queue, and select import. Don't close the importer dialog window until it completes importing.

Full walkthrough can be found [here](https://omero-guides.readthedocs.io/en/latest/upload/docs/import-desktop-client.html)

### Viewing/analyzing data
1. Login to the [web portal](http://35.8.197.106) (ignore the warning and continue).
1. [Image viewing walkthrough](https://omero-guides.readthedocs.io/en/latest/iviewer/docs/iviewer_viewing.html)
1. [Making ROIs](https://omero-guides.readthedocs.io/en/latest/iviewer/docs/iviewer_rois.html)
1. Fiji
   - [Guide](https://omero-guides.readthedocs.io/en/latest/fiji/docs/manual_analysis.html)
   - [Example Jupyter Notebooks](https://github.com/ome/omero-guide-fiji)
1. Python
   - [Guide](https://omero-guides.readthedocs.io/en/latest/python/docs/index.html)
   - [Example Jupyter Notebooks](https://github.com/ome/omero-guide-python)
   - [Detailed developer guide](https://docs.openmicroscopy.org/omero/5.6.3/developers/Python.html)

For more information see the [OMERO Documentation](https://omero-guides.readthedocs.io/en/latest/index.html)

## Example notebooks
- [OMERO Hello World](https://github.com/Jsakkos/microtools/blob/main/notebooks/OMEROHelloWorld.ipynb)
- [Segmentation](https://github.com/Jsakkos/microtools/blob/main/notebooks/Segmentation.ipynb)
- [Average Cell](https://github.com/Jsakkos/microtools/blob/main/notebooks/Average%20cell%20from%20mask.ipynb)
