# Robot_Cello_Sim

Create a ROS2 Worspace if one doesn't exist:
```
mkdir ~/ros2ws/src
```

Clone Repo:

```
cd ~/ros2ws/src
```

```
git clone https://github.com/Ranasinghe843/Robot_Cello_Sim.git
```


Move cello to models database:

```
mv ~/ros2ws/src/Robot_Cello_Sim/robot_cello_sim/models/cello ~/.gazebo/models/cello
```

Build and source workspace:
```
cd ~/ros2ws
```

```
colcon build
```

```
source ~/ros2ws/install/local_setup.bash
```

Run the simulation:

```
ros2 launch robot_cello_sim ur5e_sim_control.launch.py
```

Run the simulation (with moveit):

```
ros2 launch robot_cello_sim ur5e_sim_moveit.launch.py
```
