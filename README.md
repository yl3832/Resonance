# Resonance

Resonance Homework 

+ **Project Title**: Resonance - Labelling Image Color Body and Style  
+ **By**: Yilin Lyu: Columbia University (yl3832@columbia.edu)

___
+ **Summary**:  
  + There are three tables to be labeled including **_Color, Body_** and **_Style_**. 
  + For the images in Color table, to be labeled: **_Brightness, Contrast, Color, Field, Genre_**
  	+ Use existing *OpenCV measurement* to label **Brightness and contrast**.
  	+ Use *K-Means* to find the dominant colors in images as the labels for **_color_**.
  	+ Use image *segmentation* to find the **_field_**.
  	+ Use *KNN* to find the **_genre_** of the picture. 
  + For the images in Body table: 
  	+ Use *KNN* to find the closest descriptions with top frequencies to the target image as the body tags.
  + For the images in Style table:
  	+ Notice that we could add tags to the **style** dataset according to **_Resonance_code_**
    A **Resonance_code** includes three parts: *body_tag_code* + *material_tag_code* + *color_tag_code*.
    For example: a cloth with Resonance_code: CM-3003 SGT19 WHITUI means:
		+ ZIP HOODIE (CM-3003) with hite w/Thin Navy Vertical Stripe (WHITUI)

___


+ **Examples of labelling results**:  
  + Prediction of Color Image: 

  <img src = './figs/test_4.png'  width="300" height="300">   <img src = './figs/predictions_of_test_4.png' width="300" height="300">
 	 
  + Prediction of Body Image: 

  <img src = './figs/test4.png'  width="300" height="300">
  <img src = './figs/predictions_of_test4.png'>



```
proj/
├── notebook/ 
├── figs/  
├── visualizations/ 
├── results/ 
```
