# Flower Image Classifier Project

My final project for Udacity's AWS AI/ML Programming with Python Nanodegree Program.

This project, developed for an Udacity AI course, utilizes a deep learning network to classify flowers based on provided labels. The project unfolds in two distinct phases:

### Training the Neural Network:

- Choosing the Right Architecture: I begin by selecting a neural network architecture that's well-suited for image classification tasks. This involves considering factors like model complexity, accuracy, and computational efficiency.

- Harnessing GPU Power: To accelerate the training process, I leverage the powerful parallel processing capabilities of a GPU (Graphics Processing Unit). This allows me to train the model more efficiently and quickly.

- Learning from Experience: The model is trained iteratively on a dataset of labeled flower images. With each iteration, it learns to identify patterns and features that distinguish different flower types.

- Saving for Future Use: Once the model has achieved a satisfactory level of accuracy, I save it for future use. This allows me to quickly deploy the trained model without having to retrain it from scratch.

### Testing and Transferring Knowledge:
- Loading the Saved Model: I load the previously trained model from memory, ready to tackle new flower images.

- Putting It to the Test: I provide the model with unseen flower images to evaluate its ability to generalize and correctly classify them.

- Standing on the Shoulders of Giants: To further enhance the model's performance, I employ transfer learning. This involves leveraging pre-trained classifiers from the PyTorch package, which have already acquired a wealth of knowledge from massive image datasets. I adapt these classifiers to our specific flower classification task by adjusting their final layers.

Files Included:
These are the files included as part of the project and what each contains:

ImageClassifierProject.ipynb: This is the Jupyter notebook where I conducted all my activities, including a little more than what is included in the predict.py and train.py files.

ImageClassifierProject.html: It is the same as the file above, in HTML form.

train.py: This file accepts inputs from the command line prompt and will train a new network on a dataset and save the model as a checkpoint.

predict.py: This file accepts inputs from the command line prompt and uses a trained network (i.e vgg19) to predict the class for an input image.
