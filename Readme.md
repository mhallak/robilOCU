Running OCU: givingWayPoints.html
Description: open map, draw path on the map, the path go to the server and is converted in ROS topic
1. roscore
2. roslaunch rosbridge_server rosbridge_websocket.launch
3. Open OCU  (open givingWayPoints.html in Chrome or Firefox)
4. See results in the topic: /move_base/TrajectoryPlannerROS/global_plan (rostopic echo )

Running OCU: firstVersionOCU.html
Description: open map, get bobcat initial coordinates, draw path on the map, a simple goal topic is sent to the the server and is converted in ROS topic and the bobcat moves!!!!! (in the simulation)
1. roslaunch live_bobcat bobcat_tracked_static_arm_empty_world.launch
2. roslaunch robil2conf frameworkInit.launch
3. roslaunch rosbridge_server rosbridge_websocket.launch
4. Open OCU  (open firstVersionOCU.html in Chrome or Firefox)
5. See results in Gazebo: the bobcat moves

