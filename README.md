# Launch a terminal

$ sudo apt install python3-pip

$ pip3 install ultralytics

$ sudo apt install python3-colcon-common-extensions

$ sudo apt install ros-humble-gazebo-*


$ cd ~

$ git clone https://github.com/wildchildfeel/yolobot.git

$ cd yolobot

$ cp -r models/ ~/.gazebo/models/


$ colcon build

$ source ~/yolobot/install/setup.bash

$ ros2 launch yolobot_gazebo yolobot_launch.py

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/38a0dd39-8b7c-4a55-8588-5d3cd6ed1afa)

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/f5f3f964-8182-417e-a6b7-4d894566b41f)



# Launch a new terminal
$ source ~/yolobot/install/setup.bash

$ ros2 topic echo /Yolov8_Inference

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/cf5599ed-db3e-402b-bfcf-a0bc871ce9e2)



# Launch a new terminal
$ rviz2

- Click "Add" & "By topic"
- Select "/inference_result, Image"

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/0a5cbb88-cfa4-4091-924f-044cfc9cdf55)
![image](https://github.com/wildchildfeel/yolobot/assets/156588748/ea546e50-1c7f-4cfd-8b18-b2939506f42c)

