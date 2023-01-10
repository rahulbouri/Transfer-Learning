# Transfer-Learning

## Model 1: using SKLearn

We have data collected in the data.csv file. It contains information regarding a Heat Transfer process where we measure different features such as inner diameter, outer diameter, length, orientation and heat supplied to pipe. All this information is used to predict the Thermal Resistance of the pipe. We use the simple SKLearn Randomized Search CV Model.

## Model 2: using Pytorch

Implemented Transfer Learning using PyTorch documentation. The task is to distinguish between 'Ants' and 'Bees'. We use pretrained ImageNet Conv Net and then use the ConvNet either as an initialization or a fixed feature extractor for the task of interest.

For code/redources/guidance the following repository was referred: https://github.com/pytorch/tutorials/blob/master/beginner_source/transfer_learning_tutorial.py
