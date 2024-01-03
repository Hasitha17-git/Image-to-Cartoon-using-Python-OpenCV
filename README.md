# Image-to-Cartoon-using-Python-OpenCV
## Abstract
The proposed mini project is an image to cartoon python OpenCV machinelearning that converts uploaded images to cartoon style versions using machinelearning algorithms. The main objective of the project is to provide an easy to use and accessible tool for users to convert their images to cartoons. The major goal is to produce a final product that may be used to transformreal-worldimages into animated prints (cartoon images). The idea behind the paper is built around original images and videos that are then transformed into an artistic for makin to oil. Among all the techniques available, the operation of a GenerativeAdversarial Network (GAN) dubbed Cartoon GAN may be employedfor the styling of real-world images that employ two loss functions—happy loss and hostile loss—to obtain a clean and clear image. While creating the layout, this project would use the OpenCV library in Python. Python is a library collection with multiplex libraries for operations in the real world. OpenCV is one suitable library.
## Required modules in this Project
- CV2: Imported to use OpenCV for image processing
- easygui: Imported to open a file box. It allows us to select any file fromoursystem.
- Numpy: Images are stored and processed as numbers. These are takenasarrays. We use NumPy to deal with arrays.
- Imageio: Used to read the file which is chosen by file box using a path.
- Matplotlib: This library is used for visualization and plotting. Thus, it isimported to form the plot of images.
- OS: For OS interaction. Here, to read the path and save images tothat path.
- Flask: Flask is a micro web framework written in Python.

## REQUIREMENT SPECIFICATIONS
### HARDWARE REQUIREMENTS
- Hard disk : 500 GB and above.
- Processor : i3 and above.
- Ram : 4GB and above.
- Webcam
### SOFTWARE REQUIREMENTS
- python 3.7
- tensorflow 2.1.0 
- tf_slim 1.1.0
- ffmpeg 3.4.8
- Cuda version 10.1
- OS: Linux (Ubuntu 18.04), Windows 10

## Installation

### Using `virtualenv`

1. Make a virtual environment using `virutalenv` and activate it
```
virtualenv -p python3 cartoonize
source cartoonize/bin/activate
```
2. Install python dependencies
```
pip install -r requirements.txt
```
3. Run the webapp. Be sure to set the appropriate values in `config.yaml` file before running the application.
```
python app.py
```
