# Learning ROS2

## Installation

- Chose correct ROS2 distro for the operating system  
I chose https://index.ros.org/doc/ros2/Releases/Release-Eloquent-Elusor/, for ubuntu 18.04

- Install ROS2 packages (https://index.ros.org/doc/ros2/Installation/Eloquent/Linux-Install-Debians/)  

- Source ROS2 setup script in shell session (.bashrc)  
`source /opt/ros/eloquent/setup.bash`

- Install colcon build  

```sudo apt install python3-colcon-common-extensions```

- Source colcon argcomplete (add it to .bashrc)
/usr/share/colcon_argcomplete/hook/colcon-argcomplete.bash

## Write ROS2 program

- Create a ROS2 workspace (convention is `~/ros2_ws/src`)  
It can be built using `colcon build`.  (source setup.bash in install folder of the workspace, to easily run ROS nodes)

- Create ROS2 package (python/c++)

- Create Nodes within the package (Nodes are dynamically created)

- Create entry points for executables / binaries (so that they can be launched from ros2 cli tools)
