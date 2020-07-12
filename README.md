# ROSStudy
### ROS Notes

## Find ROS Packages
#### A good way to check is to ensure that environment variables like ROS_ROOT and ROS_PACKAGE_PATH are set: 
> printenv | grep ROS

## Before running catkin_make of new source file
#### make sure you run below command once in every new session inside Catkin_ws
> sukumaran@sukumaran-Lenovo-ideapad-330-17ICH:~/catkin_ws$ source devel/setup.bash
#### make sure ROS path is included to the current working sandbox
> echo $ROS_PACKAGE_PATH
## Visualise Node and topics
   > rqt_graph
## Create


----
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ2MDcyMzU5MSwtNTA5OTExNzk5LC0xNz
k4MzQ1NTc3XX0=
-->