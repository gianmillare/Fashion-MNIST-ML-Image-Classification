# Fashion-MNIST-ML-Image-Classification

One of the first courses I took on Machine Learning was an [Image Classification course](https://github.com/gianmillare/Image-Classification-with-Tensorflow-Guide) that used the MNIST library to predict an image of a number. I decided to expand on the lessons I learned from that course here. 

In this project, I took the [Fashion-MNIST library](https://www.kaggle.com/zalando-research/fashionmnist) and applied machine learning techniques to build a model to predict an article of clothing depicted in an image. The objective is to display what I learned from that course, and build a model that outputs at least an 85% accuracy (both model output and evaluation) with the least amount of loss.

The model built here acheived the accuracy objective, however, I feel the loss associated with the model could have been minimized a bit further. 

This was a quick and dirty mini-project that I used to test my skills, so I accepted the model at it's current state for time's sake. If this project were to be expanded, I would like to try other neural network models, adding in more hidden layers, and (if possible) running more epochs while avoiding over (and under) fitting.

Please view the entire Jupyter notebook [HERE](https://nbviewer.jupyter.org/github/gianmillare/Fashion-MNIST-ML-Image-Classification/blob/main/project.ipynb)!

Credited Course: [Coursera Projects](https://www.coursera.org/learn/tensorflow-beginner-basic-image-classification/home/welcome)  
View other projects: [Data Science Projects](https://github.com/gianmillare/AI-ML-Data-Science-Projects)  
View my Course Notes: [Data Science Lessons](https://github.com/gianmillare/AI-ML-Data-Science-Guides)

<hr>

### The Fashion-MNIST library comes with 10 different articles of clothing. Below is a sample.
![](images/data.png)

<hr>

### I trained the model for 15 Epochs. I felt that 5 was too few, and 50 was over-fitting. As mentioned, the loss can be minimized further.
![](images/training.png)

<hr>

### Below is a visualization of the predictions. 22/25 were correct, making 88% accuracy for this sample.
![](images/plotting.png)
