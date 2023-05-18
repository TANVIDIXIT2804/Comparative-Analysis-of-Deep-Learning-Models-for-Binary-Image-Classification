Assignment 5
PUBLISHED
March 26, 2023

In this question, you have to compare the performance on a binary classification task of the following models:

VGG (1 block)
VGG (3 blocks)
VGG (3 blocks) with data augmentation
Transfer learning using VGG16 or VGG19
Refer this article You do not need to write your own code. You can reuse the code from the post. Or, you could roll out your own implemenation. Either way, you should be able to explain your code during the viva.

You need to create the dataset on your own based on your first names. For instance if the first name of the team members are: Siya and Raghav, they can choose a dataset of their liking based on any names, place, animal or thing. As examples:

Seoul v/s Riyadh
Snake v/s Rat
Squirrel v/s Rabbit
Sambhar v/s Roti
You can refer to resource 1 or resource 2 or plainly download 100 images of both classes (total 200 images). Of these 100 images of each class, we will use 80 for training and 20 for testing. You get 1 mark for dataset creation [1 mark]

Create a table with models as rows and the following columns [2 marks (0.5 marks for each model)]

Training time
Training loss
Training accuracy
Testing accuracy
Number of model parameters
We will now be using Tensorboard for visualizing network performance. You are suggested to refer to:

PyTorch + Tensorboard
Tensorflow + Tensorboard
Use Tensorboard to log the following and present screenshots/images [1 mark]

Scalars

Training loss v/s iterations (and not epochs)
Training accuracy v/s iterations (and not epochs)
Testing accuracy v/s iterations (and not epochs)
Images

Show all images from the test set and their predictions
Now you have to present various insights. For instance, you should discuss the following: [2 marks (0.5 marks for each question)]

Are the results as expected? Why or why not?
Does data augmentation help? Why or why not?
Does it matter how many epochs you fine tune the model? Why or why not?
Are there any particular images that the model is confused about? Why or why not?
Now, create a MLP model with comparable number of parameters as VGG16 and compare your performance with the other models in the table. You can choose the distribution of number of neurons and number of layers. What can you conclude? [1 mark]
