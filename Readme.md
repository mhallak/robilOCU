Running OCU: givingWayPoints.html
Description: open map, draw path on the map, the path go to the server and is converted in ROS topic
1. roscore
2. roslaunch rosbridge_server rosbridge_websocket.launch
3. Open OCU  (open givingWayPoints.html in Chrome or Firefox)
4. See results in the topic: /move_base/TrajectoryPlannerROS/global_plan (rostopic echo )


