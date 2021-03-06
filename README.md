# Venue-Category-Estimation-from-Micro-videos
We released the dataset for venue category estimation from micro-videos.

# Introduction
   Micro-videos spread rapidly across various onlineflagship platforms, such as Instagram,Snapchat, and Vine, since the late of 2012. We aim to label such bite-sized video clips with venue categories.In this repository, we relased a rich set of feature extracted from micro-videos which crawled from Vine. In particular,our dataset is consisting of 270,145 micro-videos distributed in 188 Foursquare venue categories (VENUE-188 for short). We further splited VENUE-188 into training,valid,and testing data in a ratio of 50%, 20%,and 30%, with a number of 132370,56730,and 81044,respectively. Besides,the corresponding videos-ids were also recorded in the dataset.

# Tasks
  There are several research tasks can be conducted in the VENUE-188.
  1) multi-modal venue category estimation
    
  2) mono-modal venue categry estimation
  
  
# Contents
  1) The labels (from 1-188) and their corresponding venue cateogries classes;
  
  2) alex_net: alexnet_visual_feature (4096 dim) + stacked_denosing_autoencode_feature(200 dim) + paragraph_textual_feature(100 dim). You can access this feature set via this link:.
  
  3) inception_v3: inceptionV3_visual_feature (2048 dim) + stacked_denosing_autoencode_feature(200 dim) + paragraph_textual_feature(100 dim). You can access this feature set via this link:https://pan.baidu.com/s/1c2vh1DI.
  
  4) vgg19: vgg19_visual_feature (512 dim)+ stacked_denosing_autoencode_feature(200 dim) + paragraph_textual_feature(100 dim).You can access this feature set via this link:https://pan.baidu.com/s/1kULbYMr
  
  5) resnet50: resnet50_visual_feature (2048 dim) + stacked_denosing_autoencode_feature(200 dim) + paragraph_textual_feature(100 dim). You can access this feature via this link:https://pan.baidu.com/s/1mhS0Pp2.
  
  6) video description:user generated text and hashtags:https://pan.baidu.com/s/1bpnbWAz.
  
  7) video url:the url of all downloaded videos.https://pan.baidu.com/s/1mioMh4W.
  

# Citation
Please cite it as...
```
@inproceedings{Zhang2016Shorter,
  title={Shorter-is-Better: Venue Category Estimation from Micro-Video},
  author={Zhang, Jianglong and Nie, Liqiang and Wang, Xiang and He, Xiangnan and Huang, Xianglin and Chua, Tat Seng},
  booktitle={ACM on Multimedia Conference},
  pages={1415-1424},
  year={2016},
}
```
# License
   1) All code in this repository is under the MIT license as specified by the LICENSE file.
   2) The ResNet50 weights are ported from the ones released by Kaiming He under the MIT license.
   3) The VGG16 and VGG19 weights are ported from the ones released by VGG at Oxford under the Creative Commons Attribution License.
