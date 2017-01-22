## Project: Build a Traffic Sign Recognition Program
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)
### Overview

In this project, you will use what you've learned about deep neural networks and convolutional neural networks to classify traffic signs. You will train a model so it can decode traffic signs from natural images by using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). After the model is trained, you will then test your model program on new images of traffic signs you find on the web, or, if you're feeling adventurous pictures of traffic signs you find locally!

### Dependencies

This project requires **Python 3.5** and the following Python libraries installed:

- [Jupyter](http://jupyter.org/)
- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/)
- [scikit-learn](http://scikit-learn.org/)
- [TensorFlow](http://tensorflow.org)
- [Matplotlib](http://matplotlib.org/)
- [Pandas](http://pandas.pydata.org/) (Optional)

### Installing/Starting on local workstation

Switch to the directory after CarND-Traffic-Sign-Classifier-Project after cloning and install the environment:

- `conda env create -f environment.yml`

Run this command at the terminal prompt to install [OpenCV](http://opencv.org/). Useful for image processing:

- `conda install -c https://conda.anaconda.org/menpo opencv3`

Activate the enviroment

- `source activate CarND-Traffic-Sign-Classifier-Project`

### Running on AWS GPU Instance

* Start the instance in the [AWS console](https://eu-central-1.console.aws.amazon.com/ec2/v2/home?region=eu-central-1#Instances:sort=instanceId) (Actions -> Instance State -> Start)
* Write down the public IP
* Open a terminal on the local workstation and ssh into the instance: `> ssh carnd@<public IP>`
* Password is `carnd`
* `cd CarND-Traffic-Sign-Classifier-Project/`
* `source activate CarND-Traffic-Sign-Classifier-Project`
* `jupyter notebook`
* Open `http://<public IP>:8888/` in a browser on the local workstation


### Dataset

* [Download the dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip). This is a pickled dataset in which we've already resized the images to 32x32.
