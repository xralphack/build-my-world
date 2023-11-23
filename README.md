## How to run this project?

* enter the local directory of the cloned project
* mkdir build
* cd build
* cmake ../
* make
* export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/[somewhere]/build-my-world/build
* cd ../world
* gazebo myworld --verbose
