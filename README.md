# MASKRCNN_TF_V2
Upgraded MASKRNN python files to Tensorflow V2


Reference :

https://github.com/matterport/Mask_RCNN

Fixes :

MASK RCNN -> Model.py was created with older version of Tensorflow, So the following functions throws error

  tf.random_shuffle()
  tf.logs() etc.
  
  To avoid these error,we need to upgrade MASK RCNN Project folder to Tensorflow V2.2.0 
  
  Refer the below guide for Tensorflow Upgradation.
  https://www.tensorflow.org/guide/upgrade
  
  In this Reposiroty, I have uploaded the upgraded files of Mask RCNN.
