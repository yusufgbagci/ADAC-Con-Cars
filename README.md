# ADAC-Con-Cars

Clone acdc Repository
Start a terminal on your Linux/MacOS system and navigate to a directory where you want to store the acdc repository.
If you have never used a Unix-Shell (terminal) before, we strongly suggest you to do an [online tutorial](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)  before you start this course.

We suggest you to navigate to the directory ~/Documents which is located in you home directory and clone the acdc repository there with the following command

'''
git clone --recurse-submodules https://github.com/ika-rwth-aachen/acdc.git
'''

After cloning, your local acdc directory should have the same contents like you can see in the following:

'''
├── assets
│   └── header_image.png
├── bag
│   ├── .gitkeep
├── catkin_workspace
│   └── src
├── colcon_workspace
│   └── src
├── docker
│   ├── dockerfile
│   ├── Makefile
│   ├── ros_entrypoint.sh
│   └── run.sh
├── .git
├── .gitignore
├── .gitlab-ci.yml
├── LICENSE
└── README.md
'''

## Install Docker

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers are a standardized unit of software that allows developers to isolate their application from its environment and distribute safely it to any other environment. For the ACDC course, we created such a standardized container that allows every student to run our code without any manual installations of libraries or other programs. The requirements to use our container are an installation of Docker Version 19.03 or later.

"""
https://docs.docker.com/engine/install/ubuntu/
"""
Test your installation of docker with
"""
sudo docker run hello-world
"""
Now it should work without sudo(You need to restart your machine after the previous step):
