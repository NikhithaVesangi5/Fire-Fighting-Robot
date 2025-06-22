
# Fire Fighting Robot

# [WorkingPrototype]
![Image](https://github.com/user-attachments/assets/e8832487-63d2-47f3-9ccb-78be2cf91071)


rview:
This case study uses PostgreSQL. To successfully answer all the questions one should have exposure to the following areas of SQL:

* Our robot is to enter a “place” and seek out a spot where there is extreme heat possibly due to a fire.

* The locations of the doors are initially unknown to the robot.

* Once the robot has driven up to the light source, the fire sensor is activated to check and see if there is a large amount of
fire being generated.

* If there is an excessive amount of fire generated, the water from tank will be turned on and sprinkle water quickly with a
servo motor to put out the flame.

* If the flame is not put out the water will turn on again and continue to sprinkle on the flame.

* Once the flame is extinguished, the robot leaves the home.

* If the fire sensor does not find excessive heat it will leave the room.

# Questions
1) How does the robot detect fire?
2) How does the robot navigate towaed the fire?
3) What programming language and components did you use?
4) What challenges did you face during the project?
5) Is the robot autonomous or manually controlled?
6) Can the robot detect multiple fire sources?
7) How is the water released to extinguish the fire?
8) What are potential real-world applications?


# Approach :- 

* We designed and developed an autonomous fire-fighting robot using Arduino and C. The robot uses flame sensors to detect the presence and direction of fire.
* Based on the sensor input, the Arduino controls the movement of DC motors to navigate toward the fire source. Once the robot reaches the flame, a water pump is activated to extinguish it.
* The system is powered by a battery and built for real-time response in emergency scenarios.
