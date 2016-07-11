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


##[Oxford flower 102](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)


### Evaluation



### results
1[Two-Stream Contextualized CNN forFine-Grained Image Classification] (https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11772/12231) reports **94.5** based on fusion architecture(roughly image + segmentation or image and context)
