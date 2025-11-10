# Model Building for Computer Vision

## Project Description:
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. 
You are asked to conduct that evaluation, so as you set to work, keep the following in mind:
- The shops are equipped with cameras in the checkout area which are triggered when a person is buying alcohol
- Computer vision methods can be used to determine age of a person from a photo
- The task then is to build and evaluate a model for verifying people's age
- To start working on the task, you'll have a set of photographs of people with their ages indicated.

It is very useful to conduct EDA before rushing into modelling, even while working with sophisticated models like neural networks.
As the number of image files is rather high, it is advisable to avoid reading them all at once, which would be resource consuming, and to read them sequentially with the ImageDataGenerator generator. 

# Instructions:
1. Perform exploratory data analysis to get an overall impression of the dataset.
    - Look at the dataset size.
    - Explore the age distribution in the dataset.
    - Print 10-15 photos for different ages on the screen to get an overall impression of the dataset.

2. Train and evaluate the model (it needs to be done on the GPU platform).
    - load_train(path) - it loads the train dataset
    - load_test(path) - it loads the test dataset
    - create_model(input_shape) - it defines a model
    - train_model(model, train_data, test_data, batch_size, epochs, steps_per_epoch, validation_steps)

3. Provide findings on how the specifics of the dataset you discover may affect how the model is trained.


# Key Concepts:
🗝️ Data Interpreation using Image Generator like ImageDataGenerator

🗝️ Model building and training on GPU platform.

🗝️ Using tensorflow.keras library


# What I Learned:
✔️ GPU Platform vs CPU Platform

✔️ How to read image files and print them into notebook

✔️ Model building using image recognition and data intrepretation

✔️ For cases when human vision is lacking, computer vision can be significant
