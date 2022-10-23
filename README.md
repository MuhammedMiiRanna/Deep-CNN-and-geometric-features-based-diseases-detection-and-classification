# Deep-CNN-and-geometric-features-based-diseases-detection-and-classification

A scientific article named: Deep CNN and geometric features-based gastrointestinal tract diseases detection and classification from wireless capsule endoscopy images, i'am realizing it as aCollege project for My first year as a Master Computer vision students, USTHB.

# Team handlers

- Mohamed Ali Merali
- Ms I. Setitra (Image analysis and Deep learning teacher supervisor)

# Last update

- initializing the Project

# ABSTRACT

Gastrointestinal tract (GIT) infections such as ulcers, bleeding, polyps, Crohn’s disease and cancer are quite familiar today worldwide. Wireless capsule endoscopy (WCE) is an efficient means of investigation of GIT diseases. However, still several challenges exist in this domain, such as lesion shape, colour, texture, size and irregularity. To deal with these problems, several computer-based methods are introduced in computer vision domain but they used only hand-crafted features which produced wrong predictions several times. 

In this research, a new technique is applied based on the fusion of deep convolutional (CNN) and geometric features. Initially, disease regions are extracted from given WCE images using a new approach named contrast-enhanced colour features . Geometric features are extracted from segmented disease region. Thereafter, unique VGG16 and VGG19 deep CNN features fusion are performed based on Euclidean Fisher Vector. The unique features are fused with geometric features which are later fed to conditional entropy approach for best features selection. The selected features are finally classified by K-Nearest Neighbour. 

A privately collected database which consists of 5500 WCE images is utilised for the evaluation of the proposed method and achieved best classification accuracy of 99.42% and precision rate of 99.51%. The classification accuracy proves the authenticity of the proposed approach.

# Proposed method

The proposed method involves two principal steps:

- geometric feature extraction from a segmented lesion.
- deep CNN feature extraction and fusion for classification.

To control the global contrast of input image, preprocessing is done at the very first step and then CIELAB colour features-based segmentation is performed.

In the second step, deep CNN features are computed from enhanced RGB images and fused their information which is further refined by EFV and best features selection approach. The detailed proposed design of automated system is shown in Figure 1 in the article.

# Steps briefly

1.

# Steps

1.
