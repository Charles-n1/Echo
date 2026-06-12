Vocabulaire:

- ROS: Robot operating system
- Packages: La framework utilise des blocks de code, on appelle ça un package. Ou block (dans scratch)

Tutoriel:
# Pour crée un module / package.
cd src
ros2 pkg create --build-type ament_python name
cd ..
colcon build && source install/setup.bash