  

# Oxford-IIIT-Pet_Classification

  
  

### Overview

[The Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/) is a kind of hello-word problem within FastAI community.



  

### Implementation details

| Feature | Brief Explanation |
| ------ | ------ |
| Base Model Architecture | Resnet34 from [ResNet](https://arxiv.org/abs/1512.03385) family, implementation from [PyTorch](https://pytorch.org/) |
| Learning Rate Finder | [Learning rate finder](https://arxiv.org/abs/1506.01186) implementation from [FastAI](https://www.fast.ai/) |
| Learning rate and Momentum scheduler| [One cycle policy](https://arxiv.org/abs/1803.09820) implementation from [FastAI](https://www.fast.ai/) to achieve superconvergence |
| Dataset | Dataset [The Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/) from [Visual Geometry Group (VGG)/ University of Oxford](https://www.robots.ox.ac.uk/~vgg/) |

  

  

### Results

| Model | Metrics(Accuracy) | Epochs |
| ------ | ------ | ------ |
| Resnet34 | 93.4% | 8 |


#### Confusion Matrix

![Alt text](https://github.com/gurucharanmk/Oxford-IIIT-Pet_Classification/blob/main/images/confusion_matrix.png )

  

#### Inference

![Alt text](https://github.com/gurucharanmk/Oxford-IIIT-Pet_Classification/blob/main/images/results.png )

  

## License

This project is licensed under the [MIT License](https://github.com/gurucharanmk/Oxford-IIIT-Pet_Classification/blob/main/LICENSE)
