# ubiquitous_display_description

convert xacro file to urdf file

$roscd ubiquitous_display_description/robots

$rosrun xacro xacro --inorder -o ubiquitous_display.urdf ubiquitous_display.urdf.xacro

TFの問題

urdfモデルをたち上げる前に、pan・tilt jonitを立ち上げていおく
