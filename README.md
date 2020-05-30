# MASKRCNN_TF_V2
Upgraded MASKRNN python files to Tensorflow V2


Reference :

https://github.com/matterport/Mask_RCNN

Fixes :

MASK RCNN -> Model.py was created with older version of Tensorflow, So the following functions are incompatible with Tensorflow V2

Example:
Older version [tf.random_shuffle()] => Newer version [tf.random.shuffle()]
              [tf.logs()] => [tf.math.logs()]
              
To make the code compatible with latest version of Tensorflow ,we need to replace the older version functions with newer version functions. Tensorflow has provided guide for the newer version upgradation. It reduces the manual effort.
  
  Refer the below guide for Tensorflow Upgradation.
  https://www.tensorflow.org/guide/upgrade
  
  In this Reposiroty, I have uploaded the upgraded(Tensorflow V2) files of Mask RCNN.
