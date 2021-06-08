# remote-sensing-processing-using-python
Remote sensing topics with python

### Author message:
Hi! :wave: Welcome to this repository! :bowtie: 

The objective of this repository is to use and explore the **basic concepts** of **remote sensing** using **python language**, presenting some of the most known processing methods in the world of **space technology**. Therefore, I try to bring simple geoprocessing practices and visualization of **satellite images**.

In addition, some notebooks have examples of how to calculate most common **spectral indices** using satellite imagery. Thus, I try to address relevant topics to assess **environmental subjects**. :deciduous_tree: :palm_tree: :evergreen_tree:

I hope you can somehow take advantage of the resources available here. So, let's explore several topics in remote sensing and work with **our planet!** :earth_americas:

---

The notebooks available in this repository are briefly introduced in this preview, but you will also find more detailed information about each subject diving into them. Another important remark is that all satellite imagery used during these practices are open data from the **Sentinel-2** satellites, **Copernicus constellation**.

There are currently 2 notebooks available:

#### 1. Sentinel-2-Image-processing

Basics of remote sensing using satellite imagery. How to load images, create raster composites, clip raster as well as saving to disk new raster files. We start creating **true color** composites, and then we go for a quick introduction to geopandas, when we load up a **shapefile** and use it as a **mask** to clip our true color composite.
In the end we plot the results using **matplotlib**. 

#### 2. Sentinel-2-NDVI-calculation
The second notebook tries to provide a basic understanding of how to calculate the **Normalized Difference Vegetation Index (NDVI)** using **Sentinel-2 image**. The example provided here takes the same inputs as the previous notebook, images covering the central part of the Netherlands. After an NDVI background is given, we start making a 4-band raster composite, then we use a shapefile to clip our raster, and finally, using the widely know equation for NDVI calculation, we do a math band operation to create a single-band raster with NDVI values ranging from **-1 to 1**.
