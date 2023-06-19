# :car:Lane Recognition project 
차선인식 프로젝트

 <img src="https://img.shields.io/badge/c++-00599C?style=plastic&logo=cplusplus&logoColor=white"/>  <img src="https://img.shields.io/badge/ros-22314E?style=plastic&logo=ROS&logoColor=white"/> <img src="https://img.shields.io/badge/CMake-064F8C?style=plastic&logo=cmake&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=python&logoColor=white"/>
 
## Hardware
- vehicle: Xycar N-model (http://xytron.co.kr/?page_id=500)
- vision sensor: USB camera 170' fisheye lens 640x480

## Result
- lap time: 1:26sec(lap1), 1:31sec(lap2)
- 

## Algorithm
- Vision: MovingAverage, Canny Edge, Hough Transform
- Control: PID control
- Key point
-- Dividing PID control between straight and curving lane(used different PID gains) improved the result.

## Rules
![image](https://github.com/yujin-shim/LaneRecognition/assets/108443602/f188b6da-0c18-4ab6-bf24-898183a7b1ab)
