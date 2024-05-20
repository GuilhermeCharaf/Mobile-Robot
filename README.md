git clone this repository into home
once there move the folder assess_world into home.

run this from home in terminal:
ign gazebo mobile-robotics/assess_world/assess2022.sdf -v 4

after open a new tab in therminal and cd to assess_wolrd:
cd assess_world

after run this code to spawn the robot into the gazebo assess2022.sdf:
ign service -s /world/assess/create --reqtype ignition.msgs.EntityFactory --reptype ignition.msgs.Boolean --timeout 1000 --req 'sdf_filename: "/home/ros/assess_world/src/urdf_tutorial/urdf/my_bot.urdf", name: "urdf_model"'


