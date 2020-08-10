# Airbnb Amenity Detection with DETR

![Airbnb](/images/airbnb.png)

Implementation of Airbnb's Amenity Detection using Detection Transformer(DETR). The goal of the project build an object detection pipeline for detecting amenties in a household. There are 600 classes available however we will focus on 30 classes. 

## Installation and Requirements
Run the requirements file to install dependencies. 
`pip3 install -r requirements.txt`

- Linux or macOS with Python ≥ 3.6
- PyTorch ≥ 1.4 and [torchvision](https://github.com/pytorch/vision/) that matches the PyTorch installation.
  You can install them together at [pytorch.org](https://pytorch.org) to make sure of this
- OpenCV is optional and needed by demo and visualization

### Build Detectron2 from Source

gcc & g++ ≥ 5 are required. [ninja](https://ninja-build.org/) is recommended for faster build.
After having them, run:
```
python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
# (add --user if you don't have permission)

# Or, to install it from a local clone:
git clone https://github.com/facebookresearch/detectron2.git
python -m pip install -e detectron2

# Or if you are on macOS
CC=clang CXX=clang++ python -m pip install ......
```


 
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