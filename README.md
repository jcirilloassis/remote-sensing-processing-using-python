# remote-sensing-processing-using-python
Remote sensing topics with python

### Author message:
Hi! :wave: Welcome to this repository! :bowtie: 

The objective of this repository is to use and explore the **basic concepts** of **remote sensing** using **python programming language**, presenting some of the most known processing methods in the world of **space technology**. Therefore, I try to bring simple geoprocessing practices and visualization of **satellite images**.

The notebooks have examples of how to calculate most common **spectral indices** using satellite imagery. In addition, I try to address relevant topics on **environmental subjects**. :deciduous_tree: :palm_tree: :evergreen_tree:

I hope you can somehow take advantage of the resources available here. So, let's explore several topics in remote sensing and work with **our planet!** :earth_americas:

---

The notebooks available in this repository are briefly introduced in this preview, but you will also find more detailed information about each subject diving into them. Another important remark is that all satellite imagery used during these practices are open data from the **Sentinel-2** satellites, **Copernicus constellation**.

There are currently 5 notebooks available:

#### 1. Sentinel-2-Image-processing
Basics of remote sensing using satellite imagery. How to load images, create raster composites, clip raster as well as saving to disk new raster files. We start creating **true color** composites, and then we go for a quick introduction to geopandas, when we load up a **shapefile** and use it as a **mask** to clip our true color composite.
In the end we plot the results using **matplotlib**. 

#### 2. Sentinel-2-NDVI-calculation
The second notebook tries to provide a basic understanding of how to calculate the **Normalized Difference Vegetation Index (NDVI)** using **Sentinel-2 image**. The example provided here takes the same inputs as the previous notebook, images covering the central part of the Netherlands. After an NDVI background is given, we start making a 4-band raster composite, then we use a shapefile to clip our raster, and finally, using the widely know equation for **NDVI calculation**, we do a math band operation to create a single-band raster with NDVI values ranging from **-1 to 1**.

#### 3. Sentinel-2-SAVI-calculation
The **Soil-Adjusted Vegetation Index (SAVI)** is our third example in this repository. This notebook brings an introduction discussion to **SAVI**, and how to calculate this **spectral index** using python. The imagery example given is the same tiff created during the second notebook, a **Sentinel-2 image** of the Utrecht province in the Netherlands. With a total of **4 bands** we start parsing among them, selecting only the **Red** and **NIR (near-infrared) bands** for this exercise. Lastly, we use ***matplotlib*** to display our **SAVI results**.

#### 4. Sentinel-2-Wildfire-Detection
**Wildfires** are an important phenomenon and relevant subject for study within the **climate change** subject. Considering the role of **wildfires** in the **Artic region** for **Earth's atmosphere** and **climate change**, our example study area is part of **Siberia**. In this notebook, we will see an introductory discussion of the topic and related **spectral indices**. Then, we will start coding making different calculations to **detect wildfire ocurrence**. First, we started creating **Normalized Burn Index (NBR)** products from the **current**, **pre-** and **post-fire event**. We then create a **Difference Normalized Burn Index (dNBR)** product and, at the end, we present the **burn severity map** from our case study and corresponding amount of **burnt areas** in **hectares**.

#### 5. Sentinel-2-Flood-Analysis
Monitoring **natural disasters** is one of the most important applications of **satellite remote sensing**, contributing to the response and reduction of **impacts** from **landslides** and **floods** caused by **extreme events**. **Flood analysis** can be effectively done through satellite image processing. As this **natural hazard** is very common in Asia, especially in the **monsoon season**, we make in this notebook an activity with images that cover part of the northern portion of Bangladesh. We start processing the raster images and derive the water spectral index **Normalized Difference Water Index (NDWI)**, both from the **pre-** and **post-flood** event. After, we do a more detailed analysis bringing a **change analysis** procedure, identifying where floods occurred. At the end, we calculate the **flooded areas** in **square kilometers**.
