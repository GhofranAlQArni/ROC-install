# ROC-install 


VM :

![Screenshot 2024-07-21 211624](https://github.com/user-attachments/assets/2db2117d-493d-4790-abce-872a9c526365)

![Screenshot 2024-07-21 211643](https://github.com/user-attachments/assets/be8e44f4-0600-4a5d-8466-63dc6c098ede)



__________________________________________________________________________________________________________________________________________________________________________________________


# Task 1: Installing Ubunto and ROS in a virtual machine

1. Install Oracle VM virtual box: https://www.virtualbox.org/wiki/Downloads

![Screenshot 2024-07-21 212543](https://github.com/user-attachments/assets/f26ace7f-14ca-42ea-b32a-353681fa0018)


choose the latest version and click on Windows Hosts



![Screenshot 2024-07-21 212935](https://github.com/user-attachments/assets/42763bf6-f84d-4531-bc05-c9060da58377)



# setting :

![Screenshot 2024-07-21 211839](https://github.com/user-attachments/assets/2da67d44-ac3b-4ebe-ac45-262665da5263)


![Screenshot 2024-07-21 211948](https://github.com/user-attachments/assets/411df174-9c58-470f-8993-10e5e8b1fde0)


![Screenshot 2024-07-21 212020](https://github.com/user-attachments/assets/aafc2565-7175-4d84-a1d8-db966c84158c)


![Screenshot 2024-07-21 212131](https://github.com/user-attachments/assets/ff6c1b7b-4c79-4776-b6c8-70d61a3ef3e2)


![Screenshot 2024-07-21 212207](https://github.com/user-attachments/assets/ae49e161-68dd-4083-a1eb-792df3e32db7)


# 2: Download Ubuntu 16.04.7 LTS (Xenial Xerus): https://releases.ubuntu.com/16.04/

Choose 64-bit PC (AMD64) desktop image

<img width="949" alt="image" src="https://github.com/user-attachments/assets/1aedd4f6-4323-4ad3-91b6-7ed72a0fb114">

# 3: Stetps on installing Ubunto with ROS on the virtual machine:

From the Virtual box software, click on NEW.
<img width="824" alt="image" src="https://github.com/user-attachments/assets/29556c56-de23-43b6-ab7f-4e666c54ce16">




<img width="845" alt="image" src="https://github.com/user-attachments/assets/0f0903c6-c989-4ea4-b35d-81164fb9cf6e">




# in TERMINAL ;
i. sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

ii. sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

iii. sudo apt-get update

iv. sudo apt-get install ros-kinetic-desktop-full

v. apt-cache search ros-kinetic

vi. echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc

vii. source ~/.bashrc

viii. sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential

ix. sudo apt install python-rosdep

x. sudo rosdep init

xi. rosdep update

xii. sudo apt-get install ros-noetic-catkin
























