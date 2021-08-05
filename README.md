# Gazebo-Model

It is a gazebo model of a two wheeled bot equipped with camera and laser sensor. It operates with differential drive plugin.

roslaunch two_wheeled_bot rviz.launch 

rosrun gazebo_ros gazebo 

roslaunch two_wheeled_bot spawn.launch 


rostopic list :

/camera/parameter_descriptions

/camera/parameter_updates

/camera/rgb/camera_info

/camera/rgb/image_raw

/camera/rgb/image_raw/compressed

/camera/rgb/image_raw/compressed/parameter_descriptions

/camera/rgb/image_raw/compressed/parameter_updates

/camera/rgb/image_raw/compressedDepth

/camera/rgb/image_raw/compressedDepth/parameter_descriptions

/camera/rgb/image_raw/compressedDepth/parameter_updates

/camera/rgb/image_raw/theora

/camera/rgb/image_raw/theora/parameter_descriptions

/camera/rgb/image_raw/theora/parameter_updates

/clicked_point

/clock

/cmd_vel

/gazebo/link_states

/gazebo/model_states

/gazebo/parameter_descriptions

/gazebo/parameter_updates

/gazebo/set_link_state

/gazebo/set_model_state

/initialpose

/joint_states

/move_base_simple/goal

/odom

/rosout

/rosout_agg

/scan

/tf

/tf_static
