# qr_detect
二维码检测（ros）
先提前安装好zbar库和cv_bridge
pip install opencv-python
pip install cv-bridge
pip install pyzba
sudo apt-get install ros-foxy-image-transport
然后打开摄像头
最后
ros2 run use_qr cam_qr2
如果摄像头发布的不是camera/image话题的话，就在qr_re2.py里面接受的camera/image话题更改掉
