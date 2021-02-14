# RoboND-KalmanFilterLab

![alt text](images/demo.gif)

### Dependencies

- ROS Kinetic
- CMake 2.8

### Installing ROS dependencies

```bash
$ cd <repo root>/catkin_ws
$ sudo apt update
$ rosdep install --from-paths ./src --ignore-packages-from-source -y
```

### Compiling the Program

```bash
$ cd <repo root>/catkin_ws
$ catkin_make
```

### Running the Program

```bash
$ cd <repo root>/catkin_ws
$ source devel/setup.bash
$ roslaunch main main.launch
```
