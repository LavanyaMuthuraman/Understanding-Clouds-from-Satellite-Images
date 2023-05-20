---

# Understanding Clouds from Satellite Images
#### Can you classify cloud structures from satellites?

---

<img alt="iwild" src="https://storage.googleapis.com/kaggle-media/competitions/MaxPlanck/Teaser_AnimationwLabels.gif" width="650px"/>

### **Problem Statement**

The objective of this [project](https://www.kaggle.com/c/understanding_cloud_organization) is **to develop a model that can accurately classify cloud organization patterns from satellite images.** By identifying regions in the images that contain specific cloud formations, such as **Fish, Flower, Gravel, and Sugar,** the model will assist scientists in better understanding how clouds contribute to climate patterns and aid in reducing uncertainties in climate projections. The challenge involves segmenting the regions of each cloud formation label within the test set images.

 
### **Data Fields**

The [Dataset](https://www.kaggle.com/competitions/understanding_cloud_organization/data)  provided for this competition consists of satellite images captured from NASA Worldview. The images depict regions spanning 21 degrees longitude and 14 degrees latitude and were taken from two polar-orbiting satellites, TERRA and AQUA. Each satellite passes over a specific region once a day. In some cases, an image may be stitched together from two orbits due to the small footprint of the imager (MODIS) on board these satellites. The remaining area, not covered by two succeeding orbits, is marked as black.

- Files - 9246 files
- Size - 6.41 GB
- Type - jpg, csv


In the project **"Understanding Clouds from Satellite Images**," we embarked on the task of classifying and segmenting cloud organization patterns in satellite images. By utilizing a systematic approach, we gained valuable insights and developed a model to aid in our understanding of cloud behavior and its impact on climate.

We began by importing the necessary libraries and loading the dataset, followed by conducting Exploratory Data Analysis (EDA). **EDA** involved analyzing images both with and without masks, examining the distribution of cloud formation labels, and investigating the segmented area distribution. This analysis provided a comprehensive understanding of the dataset and its characteristics.

**Segmented Area Distribution** further enhanced our understanding by exploring the number of masks per sample, shedding light on the spatial distribution of cloud formations. This knowledge was crucial for subsequent model development and evaluation.

To ensure reliable model performance, we split the dataset into train and validation sets. We then delved into model development and evaluation, where we carefully selected model parameters, implemented a data generator for efficient processing, and employed the **U-Net architecture**—a widely used model for image segmentation tasks.

Throughout the training process, we monitored the model's progress using **model loss graphs.** These graphs enabled us to visualize the training performance and make necessary adjustments for optimal results.

Applying the trained model to the test set allowed us to generate predictions for cloud organization patterns. We inspected these predictions both without background and with post-processing techniques to refine the results. This analysis provided valuable insights into the model's accuracy and identified areas for improvement.

![1_Wz8Rosw9W0VDorCwcLIxkg](https://github.com/LavanyaMuthuraman/Understanding-Clouds-from-Satellite-Images/assets/109660074/7ea10cf3-b3c2-4a9b-8cfa-d2e7c42992a4)

