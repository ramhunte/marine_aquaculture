**Potential Marine Aquaculture Habitat Along the West Coast**

The purpose of this work flow is to utilize spatial analysis tools to understand how we can identify commercial potential of natural resources. In this analysis, I am looking at how to identify potential marine species habitat suitable for aquaculture along the West Coast of the United States in each of its Exclusive Economic Zones (EEZ). I specifically look at habitat requirements across temperature and depth requirements for oysters (a widely commercially available food source) and then create a function from this analysis that can be applied to any west coast species with a given temperature and depth range and potential for aquaculture. This analysis utilizes a variety of spatial analysis tools to for both vector and raster data. These include:

* spatial subsetting 
* spatial joins
* raster reclassifiaction
* rasterization and vectorization of spatial data
* cropping and masking layers
* zonal statistics
* transforming CRS
* utilizing periodic checks 

**Note:** the data associated with this assignment is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?usp=sharing). Unzip the folder and all the contents and store in your directory as follows. Don't include data when you submit your assignment!



*Repository Structure*
```
    marine_aquaculture
    │   README.md
    │   Rmd/Proj files    
    │
    └───data
        │   wc_regions_clean.shp
        │   depth.tif
        │   average_annual_sst_2008.tif
        │   average_annual_sst_2009.tif        
        │   average_annual_sst_2010.tif        
        │   average_annual_sst_2011.tif
        │   average_annual_sst_2012.tif     
```