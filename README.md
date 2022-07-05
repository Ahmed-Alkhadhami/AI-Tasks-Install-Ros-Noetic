 # AI-Tasks-01-02
# AI-Tasks-01-02  , Install Ros Noetic on Ubuntu 20.04  :

Configure your Ubuntu repositories to allow "restricted," "universe," and "multiverse." You can follow the Ubuntu guide for instructions on doing this.




## Setup your sources.list  :
Setup your computer to accept software from packages.ros.org.  
`sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list`


## Set up your keys :
```
sudo apt install curl
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
```

## Installation :
`sudo apt update`

Now pick how much of ROS you would like to install.  
Desktop-Full Install: (Recommended) : Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages  
`sudo apt install ros-noetic-desktop-full`


## Environment setup :
You must source this script in every bash terminal you use ROS in.  
`source /opt/ros/noetic/setup.bash`


## Testing :
`source /opt/ros/noetic/setup.bash`  
`roscore`

> ![‏‏لقطة الشاشة (30)](https://user-images.githubusercontent.com/108361853/177368391-e73964e5-afac-479e-9a8e-f96e30ea2011.png)


## Extra :
Video To Help
 https://www.youtube.com/watch?v=Qk4vLFhvfbI&t=523s
