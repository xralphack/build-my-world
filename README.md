## Before run the project

* enter the local directory of the project
* `mkdir build`
* `cd build`
* `cmake ../`
* `make`
* `export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/[somewhere]/build-my-world/build`
* `cd ../world`
* `gazebo myworld --verbose`

## Note

I followed the document to create a module plugin to move the model instances inside the Gazebo world.

reference: https://classic.gazebosim.org/tutorials?tut=plugins_model&cat=write_plugin