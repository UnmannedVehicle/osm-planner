# osm-planner
## test
First,run planner_node and rviz.
```
roslaunch osm_planner planner_node.launch 
``` 

Then,control the base_link move.Provide corresponding TF conversion
```
rosrun turtlesim turtle_teleop_key
``` 

## Parameter initialization
### Select Map
Change map parameter in lanuch file
```
<arg name="map" default="map.osm"/>
``` 
### Determine the origin of map coordinates

