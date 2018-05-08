# AMR_Instruction
1. install ubuntu 16.04
1. install git
1. Set up ssh for github
  1. cd ~/.ssh
  1. ssh-keygen -t rsa -C "your_email@example.com" 
  1. source (source)[https://confluence.atlassian.com/bitbucketserver/creating-ssh-keys-776639788.html]
1. $ `at ~/.ssh/id_rsa.pub` copy this and paste in github ssh in settings
1. $`git clone git@github.com:HBRS-AMR/AMR-Wiki.git`
1. from amr-wiki/ros-installation run the  	ros_catkin_installer.sh
  1. $ chmod +x ros_catkin_installer.sh
  1. sudo ./ros_catkin_installer.sh
  1. install everything
1. Catkin workspace

Make sure you initialized your catkin workspace:

```
mkdir catkin_ws
cd catkin_ws
mkdir src
cd src
catkin_init_workspace
cd ..
catkin_make
```
and follow remaining steps ..............



## Assignments:

clone the [amr-ss18](https://github.com/HBRS-AMR/AMR-SS18) repository inside the src folder of your catkin_ws
