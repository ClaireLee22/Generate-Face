# Generate-Face
GANs Project [Udacity Deep Learning Nanodegree]

## Project Overview
### Project Description
Create a Generative Adversarial Networks(GANs) to generate new images of faces.

### Project Procedure
- Preprocess the data
  - values of dataset in the range of -0.5 to 0.5 of 28x28 dimensional images.
- Build the GANs
  - model input
  - discriminator
  - generator
  - model_loss
  - model_opt
- Train the GANs

### Project Results
- Generated images which look like realistic faces after running two epoches.

## Getting Started
### Prerequisites
This project requires **Python 3.6** and the following Python libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Tensorflow](https://www.tensorflow.org/install/pip)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)


### Run
In a terminal or command window, run one of the following commands:

```bash
ipython notebook dlnd_face_generation.ipynb
```  
or
```bash
jupyter notebook dlnd_face_generation.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data
- MNIST: contain images of handwritten digits
- CelebA: contain over 200,000 celebrity images with annotations
