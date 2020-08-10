# Airbnb Amenity Detection with DETR

![Airbnb](/images/airbnb.png)

Implementation of Airbnb's Amenity Detection using Detection Transformer(DETR). The goal of the project build an object detection pipeline for detecting amenties in a household. There are 600 classes available however we will focus on 30 classes. 
 
## Task List
- [ ] Data collection -  obtain data from Google Open Images Dataset V4 - [Link](https://storage.googleapis.com/openimages/web/download.html)
- [ ] Train an object detection model on this data using codebase from DeTr repo.
- [ ] Build an interactive web interface using Streamlit 
- [ ] Dockerizing the app using Docker
- [ ] Deploy to GCP/AWS 


## Getting Started
- Download dataset 

|First Header | Second Header|
|------------ | -------------|
|Train dataset | 34,835      |
|Test dataset | 860          |
|Validation dataset | 2,493  |


## Resources 
1. [Amenity Detection and Beyond — New Frontiers of Computer Vision at Airbnb](https://medium.com/airbnb-engineering/amenity-detection-and-beyond-new-frontiers-of-computer-vision-at-airbnb-144a4441b72e) 
2. [DE⫶TR: End-to-End Object Detection with Transformers](https://github.com/facebookresearch/detr)
3. [Replicating Airbnb's Amenity Detection with Detectron2](https://github.com/mrdbourke/airbnb-amenity-detection)