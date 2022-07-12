# DeepLearning21FallFinalProj
The ability to automatically identify objects is a vital task for
autonomous driving. In addition to requiring high accuracy
(like humans), object detection for autonomous driving also
requires very short computation time. This ensures the vehicle
can promptly react in a split second to keep passengers
and pedestrians safe. Deep learning models must be trained
on large datasets of 2D images and 3D data to improve the
accuracy of object detection and compute time. Even with
large datasets, autonomous vehicles are not ready for commercial
use and researchers are still improving on their deep
learning models. It could take years until the models are
fully mature to be used on public roads.

Our project intends to replicate autonomous vehicles on
2D image datasets and break up our goal into three stages.
The first stage would be the ability to detect other vehicles,
pedestrians, and bicyclists. The second stage would
be detecting road infrastructure such as road lanes, signs,
and streetlights. We will create a bounding box or segmentation
around the object the model is trained on. The third
stage would be testing our model on our images/videos of
New York City. We would like to see how the model accuracy
will differ if we change the camera angle to a position
the model was not trained on. We intend to train our model
on KITTI dataset, Waymo dataset and Berkeley DeepDrive
(BDD) dataset.
