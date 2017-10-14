#    基于ROS系统的通用两轮底盘开发包
（Google cartographer 建图，导航，与底盘驱动接口程序包）

************** Download and bulid files **************************

    $ cd ~/
    $ mkdir webot
    $ cd webot

    $ sudo git clone git@github.com:ROS-Robotics/src.git

    $ chmod -R 777 ./src/

    $ catkin_make_isolated --install --use-ninja

***********************************
        Run a demo  
***********************************        

$ source ~/webot/install_isolated/setup.bash

$ roslaunch webot webot_SLAM_test.launch