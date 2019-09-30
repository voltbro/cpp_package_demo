# cpp_package_demo

Пример пакета для работы c .cpp файлами на RaspberryPi + ROS melodic

### Установка и билд пакета
```
cd ros_catkin_ws/src
git clone https://github.com/voltbro/cpp_package_demo
cd ../
cp ./src/cpp_package_demo/extra/build.sh build_cpp.sh
./build_cpp.sh
```

### Запуск
```
roslaunch cpp_package_demo topic_subscriber
```
