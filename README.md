# Turtlebot3 with SLAM Simulation

## Steps of Use Turtlebot3 with SLAM Simulation:

- **Step-1:** Launch Simulation World



 <!-->

         export TURTLEBOT3_MODEL=burger

![image](https://user-images.githubusercontent.com/85820553/128572179-24a8bf67-8eca-4d86-b90d-d6f99521f3ca.png)


 <!-->

         roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping

![image](https://user-images.githubusercontent.com/85820553/128573016-04122dea-d6e3-4b5d-9101-e835ebcf6375.png)



![image](https://user-images.githubusercontent.com/85820553/128573026-e1e30d66-ee27-451d-885b-97c3dc403bbd.png)



- **Step-2:** Launch Simulation World

 <!-->

         export TURTLEBOT3_MODEL=burger

![image](https://user-images.githubusercontent.com/85820553/128573173-90e60f6f-1785-4b23-8062-93d831ea367d.png)


 <!-->

         roslaunch turtlebot3_gazebo turtlebot3_world.launch


![image](https://user-images.githubusercontent.com/85820553/128574640-1452ba34-28f4-48c9-96e0-cd94227fdd07.png)


![image](https://user-images.githubusercontent.com/85820553/128574671-b4cd457a-0b87-4715-8224-7caf8cfe124e.png)



- **Step-2:** Run SLAM Node

  - 1- burger



 <!-->

         export TURTLEBOT3_MODEL=burger


![image](https://user-images.githubusercontent.com/85820553/128575138-91dc56b4-0de7-449a-8766-69f1422752d6.png)





 <!-->

         roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
         
         
         
         ![image](https://user-images.githubusercontent.com/85820553/128575943-cc76f127-2038-40cf-802e-c78ce0ea68bc.png)


         
         ![image](https://user-images.githubusercontent.com/85820553/128575783-bfab4ca9-9589-4219-b921-138230fbe145.png)
         
         
         
         
   - 2- waffle


 <!-->

         export TURTLEBOT3_MODEL=waffle


![image](https://user-images.githubusercontent.com/85820553/128576042-570f8ebd-001f-4910-b29d-092e9f6ae9e0.png)




 <!-->

         roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
         
         
         
![image](https://user-images.githubusercontent.com/85820553/128576251-0111776c-1dbb-463e-8008-cbbb9b56b7ea.png)
         
         
![image](https://user-images.githubusercontent.com/85820553/128576268-d7f6b60d-0092-4914-bba7-8614834cbb7f.png)





- 3- waffle_pi


 <!-->

         export TURTLEBOT3_MODEL=waffle_pi


![image](https://user-images.githubusercontent.com/85820553/128576395-e263b420-e726-420d-8187-77b494a49a1f.png)



 <!-->

         roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
         
         
         
![image](https://user-images.githubusercontent.com/85820553/128576477-93ff89f1-018a-479c-a730-a3087c515159.png)         
         
![image](https://user-images.githubusercontent.com/85820553/128576268-d7f6b60d-0092-4914-bba7-8614834cbb7f.png)





- **Step-3:** Save Map



 <!-->

         rosrun map_server map_saver -f ~/map
         
         
         
![image](https://user-images.githubusercontent.com/85820553/128578565-78d034e0-5fb6-4b9d-9271-9a5adead75f8.png)



