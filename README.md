# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2022

+ Team 4
+ Team members
	+ Shuangxian Li
	+ Fu Wang
	+ Chen Chen
	+ Christopher Halim 
	+ Chaitanya Shah


+ Project summary: In this project, we created CNN predicted model to classify images using convolutional layer and transition block for model1.
	
**Contribution statement**: 

Shuangxian Li: For model1, she created CNN predicted model to classify image data, I tried to use convolutional layer to reduce the high dimensionality of images and then used transition block between two dense blocks acts as a down sample operation, reducing the number of feature maps and the feature maps size to half. She searched and collected related paper from [Andreas Veit](https://openaccess.thecvf.com/content_cvpr_2017/papers/Veit_Learning_From_Noisy_CVPR_2017_paper.pdf) to inspire our model design process for model2.

Fu Wang implemented model 1 and model 2 by CNN with the model construction of two convolutional layers and three fully connected layers by using PyTorch. He implemented functions that take images and labels and turn them into a combined dataset suit for PyTorch. For his model 2 modification: he pre-trained CNN model by 10000 clean labels then used pre-trained model to predict labels for the rest of images and then combined new labels along with the clean labels for full model 2 training with the test accuracy of 77.70%

Chen created another CNN model for part 1 and trained the model to compare with others.

Christopher scheduled regular meetings with the group, checked and trained the models to see which one is the most appropriate, and presented the result of the project to the class.

Chaitanya Shah: Build on Shuangxian model 1 to first classify all the noisy images and then build another CNN model to classify all the images. The overall evaluation accuracy did not increase. He tried tweaking hyperparameters for his model as well as Shuangxian' model but the accuracy still did not increase. Therefore, he combined Chen's model 1 with his Model 2 and optimized further to imporve the validation accuracy. These models were finally used for the presentation and evaluation on the test set.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├──── main.ipynb
├──── model1.h5
├──── model_fin.h5
├── figs/
└── output/
```

Please see each subfolder for a README file.
