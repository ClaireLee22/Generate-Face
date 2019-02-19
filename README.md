# Generate-Face
GANs Project [Udacity Deep Learning Nanodegree]

## Project Overview
Create a Generative Adversarial Networks(GANs) to generate new images of faces.

First, using the MNIST dataset to test the GANs in order to see how well the model trains. Then running the GANs on the celebA dataset which is more complex than MNIST.

### Project Description
Generate a new TV script for a scene at Moe's Tavern using Recurrent Neural Network(RNN).

### Project Procedure
- Preprocess the data
  - Transform words to ids
  - Tokenize punctuation
- Create lookup table
- Build RNN
- Train RNN
- Generate TV script

### Project Results
- Generated TV script for a scene at Moe's Tavern successfully.
- Train on more data will get a better results.


## Getting Started
### Prerequisites
This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Tensorflow](https://www.tensorflow.org/install/pip)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)


### Run
In a terminal or command window, run one of the following commands:

```bash
ipython notebook dlnd_tv_script_generation.ipynb
```  
or
```bash
jupyter notebook dlnd_tv_script_generation.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data
```bash
data/simpsons/moes_tavern_lines.txt
```  
Part of the Simpsons dataset of scripts which consists of only the scenes in Moe's Tavern.
