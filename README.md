## Soil Suitability for Crop Rotation is California's rice growing region  
### Landsat land cover data + SSURGO Soil data + Random Forest modeling  

Most of California's Sacramento Valley has been in continuous rice production for decades. While this region maintain high yields, it is under threat from increasing pest and weed pressure, and widespread water restrictions. Crop rotation is one potential method to mitigate these issues, but but this region also has some extremely harsh soil types, making it difficult to grow non-flooded crops.  
  
We used land cover information, soil data, and a maachine learning framework to examine the suitability of the region for non-flooded crops.
   
   
![](variable_importance_plot_20220923.png)  
Variable importance (VI) scores for the soil variables used in the random forest model after 200 bootstraps. The violin plot shows the distribution of the 200 VI scores, the left and right side of the box are the upper and lower quartiles, the vertical line inside the box is the median, and the whiskers extend to 1.5 times the interquartile range. The red dot shows the VI score from the initial model execution.  
  
  
   
![](pdp_plot_20221202_EDIT.png)  
Partial dependency plots of the three most important variables in the random forest model. The grey background indicates the manually selected thresholds for each variable where the probability of rotation is higher, which we use to estimate the proportion of the continuous rice region that could accommodate rotations.  
  
  
  
![](3_panel_map_multi_legend.png)  
Map A,B, and C show continuous rice fields that meet each of the three soil criteria for rotation (pH, EC, and Ksat). Map D shows current rotated rice fields (red) and continuous rice fields that meet all three of the soil criteria.  





