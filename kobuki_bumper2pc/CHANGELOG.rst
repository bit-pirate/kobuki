^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package kobuki_bumper2pc
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.x - hydro, unstable
=======================

Forthcoming
-----------

0.4.0 (2013-08-09)
------------------
* Remove the dependency on pcl-ros. We compose sensor_msgs/PointCloud2 messages by hand, replacing pcl dependency by sensor_msgs one.
* Fixed Eigenlib alignment error on 32 bit architectures.
* Publish the pc continuously as long as bumper/cliff events are present.
* Publish stamped pointcloud.


Previous versions, bugfixing
============================

Available in ROS wiki: http://ros.org/wiki/kobuki/ChangeList
