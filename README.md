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

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/7f42ef6a-9a4e-42cb-9032-825037c0f392)

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/da6c7a2f-ebde-4624-b113-26bc5de83665)


# Launch a new terminal
$ source ~/yolobot/install/setup.bash

$ ros2 topic echo /Yolov8_Inference

![image](https://github.com/wildchildfeel/yolobot/assets/156588748/7b62afe1-d126-41d8-9548-98fe8703bbf2)


# Launch a new terminal
$ rviz2

- Click "Add" & "By topic"
- Select "/inference_result, Image"
- 
