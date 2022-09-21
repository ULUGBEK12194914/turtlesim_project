# Turtlesim installation

### First of all, make sure your system is up-to-date
ulugbekmirzabakhromov@ubuntu:~$ sudo apt update

### Install the turtlesim library
ulugbekmirzabakhromov@ubuntu:~$ sudo apt install ros-rolling-turtlesim

Reading package lists... Done
Building dependency tree       
Reading state information... Done
....
### Check that the package is installed
ulugbekmirzabakhromov@ubuntu:~$ ros2 pkg executables turtlesim

turtlesim draw_square
turtlesim mimic
turtlesim turtle_teleop_key
turtlesim turtlesim_node

### To start turtlesim, enter the following command in your terminal
ulugbekmirzabakhromov@ubuntu:~$ ros2 run turtlesim turtlesim_node

[INFO] [1663638092.636082943] [turtlesim]: Starting turtlesim with node name /turtlesim
[INFO] [1663638092.645975073] [turtlesim]: Spawning turtle [turtle1] at x=[5.544445], y=[5.544445], theta=[0.000000]



![Turtlesim simulation](https://github.com/ULUGBEK12194914/turtlesim_project/blob/main/screenshots/Screen%20Shot%202022-09-21%20at%2014.03.15.png)
