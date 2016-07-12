# Datasets, their evaluation strategy and best reported result
(May not contain the best reported result) 

## [Mit indoor 67](http://web.mit.edu/torralba/www/indoor.html)
[Indoor dataset link](http://groups.csail.mit.edu/vision/LabelMe/NewImages/indoorCVPR_09.tar)
### Evaluation 
1 As given in website
  * [TrainImages.txt:](http://web.mit.edu/torralba/www/TrainImages.txt) contains the file names of each training image. Total 67*80 images

  * [TestImages.txt:](http://web.mit.edu/torralba/www/TestImages.txt) contains the file names of each test image. Total 67*20 image

2 Other papers report creating random 10  train(80 images per class) and test (20 images per class)

### result
1 Best ONE ** 69.61**  and ONE+SVM **70.13** [related paper](http://bigml.cs.tsinghua.edu.cn/~lingxi/PDFs/Xie_ICMR15_ONE.pdf). *Test spilt is not clear from the papers apart from SUN 397 where traing and test both are N = 397*50 =20K *


##[Oxford flower 17](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)

### Evaluation

### results
1 [Flower Classification with Few Training Examples via Recalling Visual Patterns from Deep CNN](http://www.csie.ntu.edu.tw/~r01944012/cvgip15_flower.pdf)
 reports **96.84**. They use predicted images from imagenet model to augment data set and fine tune on augmented dataset.

2 [Sparse Representation Based Fisher Discrimination Dictionary Learning for Image Classification](http://link.springer.com/article/10.1007/s11263-014-0722-8)
reports **97.8 +- .7**  based an dictionary learning and assumes that images are well segmented.


##[Oxford flower 102](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)


### Evaluation


### results
1 [Two-Stream Contextualized CNN forFine-Grained Image Classification] (https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11772/12231) reports **94.5** based on fusion architecture(roughly image + segmentation or image and context)
2 [Flower Classification with Few Training Examples via Recalling Visual Patterns from Deep CNN](http://www.csie.ntu.edu.tw/~r01944012/cvgip15_flower.pdf)
 reports **90.85**. They use predicted images from imagenet model to augment data set and fine tune on augmented dataset.


## Caltech-UCSD Birds 200-2010(CUB2010)(Welinder et al. 2010)

### Evaluation
1 [Two-Stream Contextualized CNN forFine-Grained Image Classification] (https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11772/12231) reports **41.8** based on fusion architecture(roughly image + segmentation or image and context)

##  Caltech-UCSD Birds 200-2011(CUB2011)(Wah et al. 2011)

1 [Two-Stream Contextualized CNN forFine-Grained Image Classification] (https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11772/12231) reports **76.9** based on fusion architecture(roughly image + segmentation or image and context)
