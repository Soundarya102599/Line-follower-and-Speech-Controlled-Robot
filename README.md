# Line-follower-and-Speech-Controlled-Robot
Line Follower Robot is a robot that follows a line drawn on the ground to either detect a dark line on a white surface or a white line on a dark.The reflection of light on the white surface is maximum and minimum on the black surface because the black surface absorbs maximum amount of light. So, this property of light is used to detect the line. To detect light, either LDR (light-dependent resistor) or an IR sensor can be used. For this project, the IR sensor is used because of its higher accuracy. To detect the line,  two IR sensors are placed one on the left and other on the right side of the robot as marked in the diagram below. We then place the robot on the line such that the line lies in the middle of both sensors.
Infrared sensors consist of two elements, a transmitter and a receiver. The transmitter is basically an IR LED, which produces the signal and the IR receiver is a photodiode, which senses the signal produced by the transmitter. The IR sensors emits the infrared light on an object, the light hitting the black part gets absorbed thus giving a low output but the light hitting the white part reflects back to the transmitter which is then detected by the infrared receiver, thereby giving an analog output. Using the stated principle, the movement of the robot is controlled by driving the wheels attached to the motors, the motors are controlled by a microcontroller.
