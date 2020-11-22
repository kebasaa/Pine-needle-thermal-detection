

# Pine-needle-thermal-detection

A python notebook to identify pine needle-leaves on thermal images. Typical thermal images have a low resolution, the ones currenly used were captured on a FLIR A320 camera with 320x240px. Furthermore, the temperature difference between the needle-leaves and the soil background can be insufficient for efficient detection. Therefore, the following script takes regions of interest in which the images are scanned for either the reference plates used for correction of temperature measurements or needle-leaves.

The python notebooks and the data in this project are organised as follows:
1. Data is in folders:
   * Raw data: *01_rawdata*, i.e. FLIR images extracted using the _IR-data-extraction_ script (https://github.com/kebasaa/IR-data-extraction) and saved as 64-bit .tif
   * Diagnostics graphs are placed in *02_diagnostics*
   * Output is in *03_processed_data*
2. **01_detect_needles_v0.1.ipynb**: This creates the diagnostics and output data 

## Dependencies

The following python packages are required to read the FLIR files:

  - Pandas
  - Numpy
  - Scipy
  - Matplotlib

## How to Cite

Jonathan D. Muller, Tamir Dingjan. (22 October 2020). Pine-needle-thermal-detection: Tool to detect pine needle-leaves in thermal images. DOI:  (URL:
<>), Python notebook



## License

This software is distributed under the GNU GPL version 3

