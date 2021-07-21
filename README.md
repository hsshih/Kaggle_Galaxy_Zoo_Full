# Kaggle Galaxy Zoo Challenge
Predict classifications of the full [Galaxy Zoo dataset on Kaggle](https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data). 

Three methods attempted:

Galaxy Zoo 1 - CNN model, 6 convolution layers with dropouts at the end

Galaxy Zoo 2 - Create and train resnet models from scratch

Galaxy Zoo 3 - Fine tune ResNet-50 model

# Result

The fine-tuned ResNet-50 model appears to give the best predictions. Use the notebook and test image files [here](https://github.com/hsshih/Kaggle_Galaxy_Zoo_Full/tree/main/galaxy_zoo_resnet_predictions) for a quick demo of how well the predictions match the real image.
