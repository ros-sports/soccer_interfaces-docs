Soccer Vision Attribute Msgs
############################

This package provides messages for attributes for objects on a soccer field, such as balls, field markings and robots, that can be visually detected.

Such attributes can be defined separately in ``soccer_vision_2d_msgs`` and ``soccer_vision_3d_msgs``, but due to large overlap in information, this package aims to abstract out the attributes that aren't specific to 2d/3d vision.

``soccer_vision_2d_msgs`` and ``soccer_vision_3d_msgs`` depends on this package.

Messages (.msg)
***************

* Confidence
* Goalpost
* Robot
