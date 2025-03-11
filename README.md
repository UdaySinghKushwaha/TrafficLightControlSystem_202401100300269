# TrafficLightControlSystem_202401100300269

I am doing a Traffic Light Control System project, which is an imitation of how actual traffic lights work.
The system consists of three states: Red (stop), Green (go), and Yellow (caution).
Each state remains active for a particular amount of time, such as 10 seconds for Red, 7 seconds for Green, and 3 seconds for Yellow, etc.
I am utilizing a TrafficLight class to control these states.
The program initializes at Red, waits for the timer, then becomes Green, then Yellow, and lastly Red, looping back.
This is a constant loop, similar to actual traffic lights.
I am applying Python's time.sleep() to mimic the delays, and it illustrates how loops, conditionals, etc., may be employed to represent real-world systems.
