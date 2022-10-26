# 操作命令

[资料](https://fishros.com/d2lros2foxy/#/chapt3/%E5%88%86%E5%88%AB%E4%BD%BF%E7%94%A8POP%E5%92%8COOP%E5%88%9B%E5%BB%BA%E7%A9%B7%E9%AC%BC%E5%BC%A0%E4%B8%89)

## node

- cd town_ws/src
- ros2 pkg create village_li --build-type ament_python --dependencies rclpy
- colcon build --symlink-install
- ros2 run village_li li4_node

## func c++

- cd town_ws/src
- ros2 pkg create village_wang --build-type ament_cmake --dependencies rclcpp