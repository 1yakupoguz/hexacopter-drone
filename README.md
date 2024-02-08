# hexacopter-drone
The design includes an Iris with 6 wings and 2 cameras modified. Also, there is a code snippet provided for accessing the cameras without using ROS.

Aşağıdaki komutları yeni açacağınız terminalde sırasıyla çalıştırınız.

git clone https://github.com/1yakupoguz/hexacopter-drone.git
cd hexacopter-drone
sudo mv libgazebo_camera_manager_plugin.so libgazebo_gst_camera_plugin.so libgazebo_video_stream_widget.so /usr/lib/x86_64-linux-gnu/gazebo-11/plugins
unzip models
rm -r ~/ardupilot_gazebo/models
mv models ~/ardupilot_gazebo

Modeliniz kullanıma hazır, şimdi gazebo_camera_open.py dosyası içerisinde bulunan örnek kullanıma göz atarak kameraya erişebilir, frame'i kullanarak görüntü işleyebilirisiniz..
