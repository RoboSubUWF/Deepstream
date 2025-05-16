The following Deepstream file was used in conjunction with a Blue Robotics Low Light Camera. 
To use it, just add it to your DeepStream-Yolo file folder and use the following commands to run it:

cd ~/DeepStream-Yolo

deepstream-app -c deepstream_app_camera.txt


If you run into issues you may need to use some of the following commands:

sudo apt update

sudo apt install ffmpeg

sudo apt install v4l-utils
