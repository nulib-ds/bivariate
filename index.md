---
layout: index
published: true
---

## **Welcome! Let's get mapping.** 

<br>

### **Presenters**
> Kelsey Rydland - Data Science Librarian
> 
> Méch Frazier - Geospatial Specialist 
> 
> Geospatial and Data Services - Northwestern University Libraries <br>

<br>

<center>
  <h3 style="color:purple;"><a href="mailto:gis@northwestern.edu?subject=GIS support"> gis@northwestern.edu </a></h3>
</center>

<br>

> * We'll be using ArcPro and ArcOnline for today's demo. You'll need to create an ArcGIS Online account [here.](https://northwestern.maps.arcgis.com/home/index.html) To download and install ArcPro, go [here](https://www.it.northwestern.edu/software/secure/index.html). 
> 
> * ArcOnline is compatiable with Mac and Windows OS; [ArcPro](https://pro.arcgis.com/en/pro-app/latest/get-started/arcgis-pro-system-requirements.htm) is only compatiable with Windows OS
> 
> * Want to follow along the demo? [Download Data](https://northwestern.box.com/s/mhaah8qx8udzaepsm7yuiv4snagxrvy0)

<br>
  <br>
    <br>
    
<html><center><img src="https://raw.githubusercontent.com/nulib-ds/bivariate/gh-pages/img/map_scale_intro_img.jpg" width="800" height="500"></center></html>  

<br>
  <br>
    <br>

### **Goal of this workshop**
> This workshop is meant to serve as an introduction to bivariate choropleth mapping. It's a simple workshop that you should be able to replicate on your own afterwards.  

<br>
  <br>
    <br>

### **By the end of this workshop you will be able to:** 

> * Distinguish between univariate and bivariate 
> 
> * Use resources from ArcGIS Online public layer sources
> 
> * Knowledge of basic symbology functions
> 
> * Ability to make a bivariate choropleth map and layout
> 
> * Resources and support opportunities 

<br>
  <br>
    <br>
      <br>
<html><center><img src="https://raw.githubusercontent.com/nulib-ds/bivariate/gh-pages/img/univariate_map_ex.jpg" width="900" height="600"></center></html>  

<br>
  <br>
    <br>
      <br>
     <br>
   <br>
 <br>
   
<html><center><img src="https://raw.githubusercontent.com/nulib-ds/bivariate/gh-pages/img/bivariate_map_ex.jpg" width="800" height="500"></center></html>   

<br>
  <br>
    <br>
      <br>
       <br>
    <br>
 <br>
 
### **Considerations**
> * Normalize your data (!) 
> 
> * Use variables you suspect have a relationship (e.g., rainfall & diabetes vs. obesity & diabetes)
> 
> * Not statistically significant, only looking at highest vs. lowest values of overlaid variables  

<br>
  <br>
    <br>
      <br>
      
### **Data**
> * [NHGIS County Shapefile](https://data2.nhgis.org/main)
> 
> * [CDC U.S. Diabetes Surveillance System](https://gis.cdc.gov/grasp/diabetes/DiabetesAtlas.html)
> 
>   * Adults Aged 20+ Years; Age-Adjusted Percentage; U.S. Counties; 2016      

<br>
  <br>
    <br>
      <br>
      
### **To be used during demo**
> * Join fields "GEOID" from US.shp and "CountyFIPS" from Sheet1$
> * Copy and paste: Obesity and Diabetes Measures 2016 CDC
