# cifar-10-cnn

**Training a convolutional neural network on the CIFAR-10 dataset using PyTorch.**

## The why
I wanted to get my hands dirty with machine learning. I just made a linear regression model with data I scraped from Finn, but ended up spending way more time on cleaning the data than I did on actually designing the model. I wanted to spend more time tinkering with the design of my model, that is why I decided to use PyTorch and CIFAR-10.

## The how
1. I downloaded the CIFAR-10 dataset from the University of Toronto.
2. I split the dataset into training/validation/testing.
3. I designed a simple convolutional neural network with 3 convolutional layers. This model started overfitting.
4. I redesigned the model with data augmentation and dropout to counteract the overfitting.

## Results
- **ModelV1**: 72.28% validation accuracy, but overfitting.
![Result1](images/result1.png)
- **ModelV2**: 74.60% validation accuracy.
![Result2](images/result2.png)
- **Test accuracy**: Coming soon...

## Future plans
- Add batch normalization to stabilize training.
- Add spatial dropout to some of the convolutional layers.

## Requirements
```
pip install -r requirements.txt
```