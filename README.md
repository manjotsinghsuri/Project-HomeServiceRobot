# Project-HomeServiceRobot

## Follow the following Steps to launch the project 

 * ### Clone the repository
    
    ```git clone https://github.com/manjotsinghsuri/Project-HomeServiceRobot.git```

* ### Then build the packages 

    ```catkin_make```

* ### Then source it
    ```source devel/setup.bash```

Now run the various scripts in the script folder to run the localisation, mapping and homeservice part of the project.

## IMAGES of various parts

## test_slam.sh script file

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/test_slam.png "SLAM")

## test_navigation.sh script file

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/test_navigation.png "Navigation")

## pick_objects.sh script file

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/pick_objects.png "sending goals to robot")

## add_markers.sh script file

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/add_marker_1.png "adding virtual objects")

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/add_marker_final.png "adding virtual objects")

## home_service.sh script file

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/home_service_image_1.png "final home service")

![alt text](https://github.com/manjotsinghsuri/Project-HomeServiceRobot/blob/main/Images/home_service_image_2.png "final home service")

## Write-up

* In this Project i used all the knowledge provided to me in all the previous projects includeing SLAM, mapping, and everything. In this we used all the knowldege to make home service project in which we pick a object from one place and drop it in the another position.
* For completing the project I took the help of the turtlebot3 package(with some changes in it) along with the other nodes written by me.
* For localization, amcl package was used which was already in the turtlebot3_navigation package and for mapping slam_gmapping package was used.
* The ROS navigation stack creates a path for our robot based on Dijkstra's algorithm, a variant of the Uniform Cost Search algorithm, while avoiding obstacles on its path.
* To run the launch files and other files in a more efficient way, I used the script files which used xterm, which is to be installed first before using them in the laptop.
* Package named pick_objects was made in order to move the robot to the desired positon in the world using a cpp program.
* Another package add_markers was made to add virtual objects in the rviz so as to perform the task of home service in which object is to be picked and place at another position.

So except from these a lot was learned and done during the project.

Thank U !!