# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2022

+ Team 4
+ Team members
	+ Shuangxian Li
	+ Chaitanya Shah
	+ Christopher Halim 
	+ Chen Chen
	+ Fu Wang

+ Project summary: In this project, we created CNN predicted model to classify images uing  convolutional layer and transition block for model1.
	
**Contribution statement**: 

Shuangxian Li: For model1, she created CNN predicted model to classify image data, I tried to use convolutional layer to reduce the high dimensionality of images and the then used transition block between two dense blocks acts as a down sample operation, reducing the number of feature maps and the feature maps size to half. She searched and collected related paper from [Andreas Veit](https://openaccess.thecvf.com/content_cvpr_2017/papers/Veit_Learning_From_Noisy_CVPR_2017_paper.pdf) to inspire our model design process for model2.

Chaitanya Shah: Build on Shuangxian model 1 to first classify all the noisy images and then build another CNN model to classify all the images. The overall evaluation accuracy did not increase. He tried tweaking hyperparameters for his model as well as Shuangxian' model but the accuracy still did not increase. Therefore, he combined Chen's model 1 with his Model 2 and optimized further to imporve the validation accuracy.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
