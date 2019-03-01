# ubiquitous_display_description

convert xacro file to urdf file

$roscd ubiquitous_display_description/robots

$rosrun xacro xacro --inorder -o ubiquitous_display.urdf ubiquitous_display.urdf.xacro

youbotとpantiltの実行方法

$ roslaunch ubiquitous_display_description ubiquitous_display_description.launch 

$ roslaunch ubiquitous_display_pantilt start_pantilt.launch 

youBotのターミナル内で

$ roslaunch youbot_driver_ros_interface youbot_driver_for_ud.launch

TFについて

pantiltのjoints_statesは"pantilt_joint_states"

youBotのjoints_statesは"ud_base_joint_states"で

jointを追跡させています
