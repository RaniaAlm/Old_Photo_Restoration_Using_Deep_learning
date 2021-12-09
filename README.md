# Old Photo Restoration via Deep Latent Space Translation 

<img src='imgs/old_new.png'/>

Play the [Colab](https://colab.research.google.com/drive/1W2kdJLuz4GqxuEsBk5rpgDTF6YnieWob#scrollTo=11db178d) and try it on your photos :sparkles: !

## There are 4 stages to restoring the resolution of old photos :

### 1) Global Restoration (Overall Quality Improve) :

A triplet domain translation network is proposed to solve both structured degradation and unstructured degradation of old photos.

<p align="center">
<img src='imgs/pipeline.PNG' width="50%" height="50%"/>
</p>


### 2) Face Detection :

We use a landmark detection model to detect faces.

<p align="center">
<img src='imgs/Facial_Landmark_Detection.png' width="60%" height="60%"/>
</p>


### 3) Face Enhancement :

We use a progressive generator to refine the face regions of old photos.

<p align="center">
<img src='imgs/face_pipeline.jpg' width="60%" height="60%"/>
</p>


<img src='imgs/face.png'>


### 4) Blending All Stages :

In the last stage, we blend all the stages.



## Paper :
[Paper (Journal version)](https://arxiv.org/pdf/2009.07047v1.pdf)


