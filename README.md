# TASK-1-ROS
install ROS 
installing Ros 1
1- go to https://www.virtualbox.org/wiki/Downloads and download VirtualBox
2- go to https://releases.ubuntu.com/focal/ and download Ubuntu make sure it is the Ubuntu 20.04.6 LTS (Focal Fossa)(ubuntu-20.04.6-desktop-amd64.iso) version  and you need at least 1 gb ram
3-after that you need to set up the VirtualBox and choose the ubuntu-20.04.6-desktop-amd64.iso as you os and allocate hardware to it(CPU core, RAM, and local storage) 
4- go to https://wiki.ros.org/Installation/Ubuntu and follow the commands and past it in the terminal 
hint(ctrl+alt+t. is the shortcut) it is best to open the website inside the VirtualBox to make it easier
5- just copy and past the steps from 1.2 to 1.4 then choose the version you want Desktop-Full Install: (Recommended)
6-debugging: step 1.5 is to setup the environment by entering the command (source /opt/ros/noetic/setup.bash) if 
the massage said there are no file or directory appers the go back to step number 1.3(Set up your keys
) and use the command (sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys F42ED6FBAB17C654) instead you can check https://askubuntu.com/questions/1341378/invalid-signature-error-for-ros-repository-while-trying-to-do-sudo-apt-get-updat for more details
7- to make sure its working right Write the comand (roscore) .
