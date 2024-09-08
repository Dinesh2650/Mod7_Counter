Asynchronous Counter Modulo 7 - Counting Down

Project Description
This project involves designing and simulating an Asynchronous Counter that performs modulo 7 counting in a downward direction, i.e., counting from 6 to 0. The counter design uses JK flip-flops and a 7-segment display to visualize the count. This type of counter is useful in various digital systems, including timers and frequency dividers.

However, the current issue faced in this design is that the counter starts from 7 and ends at 1, instead of the desired range from 6 to 0. This repository seeks feedback and suggestions to troubleshoot this problem.

Components Involved
JK Flip-flops: These are used to build the asynchronous counter.
AND Gates: Responsible for combining certain outputs to reset the counter once it reaches 0 (modulo 7 operation).
7-segment Display: This is used to visualize the current count from 6 down to 0.
The design is implemented using a Falstad circuit simulator, and the circuit files are available for others to replicate and experiment with.

Circuit Functionality
The objective is to create a counter that:
Takes an external clock pulse as input.
Decrements from 6 to 0 (modulo 7).
Displays the current count on a 7-segment display.
Utilizes an asynchronous reset to reset the counter when the count reaches 0.
Currently, the counter counts from 7 to 1, which is not the desired behavior. This repository documents the design process and issue and seeks help for troubleshooting and correcting the problem.

Problem Statement:
The counter is designed to decrement through a modulo-7 sequence but currently has a fault where it starts at 7 and decrements down to 1, instead of starting at 6 and going down to 0.

Goal of the Project:
Correct the existing problem by ensuring that the counter starts at 6 and counts down to 0 (6 → 5 → 4 → 3 → 2 → 1 → 0).
Identify any issues in the JK Flip-flop wiring or gate logic that may be causing the incorrect behavior.
Achieve a fully functional asynchronous modulo-7 counter that operates correctly within the intended specifications.

How to Simulate
The provided Falstad Simulation Text File can be used to replicate the issue and modify the circuit in the simulator:
Download the falstad_simulation.txt file from this repository.
Visit the Falstad Circuit Simulator online.
Open the simulator and load the text file to visualize and experiment with the circuit.
Simulate to observe the current behavior (counting 7 to 1) and work on corrections.

Files in This Repository:
mod7_qn.jpg: The original problem statement from the Digital Electronics exam.
mod7_sim.png: Screenshot of the simulated circuit with the problematic behavior.
falstad_simulation.txt: The circuit file for use in Falstad Circuit Simulator.
README.md: Detailed explanation of the project, the problem, and how to simulate the issue.

How You Can Contribute
I am seeking help from anyone with expertise in digital electronics, counter design, or JK flip-flop logic to:
Identify and correct the issue where the counter starts from 7 and ends at 1.
Suggest modifications in the design, specifically in the reset logic or flip-flop control signals.
Provide feedback or alternative designs for a more efficient solution.

Future Goals
Once the issue is resolved, the plan is to:
Document the solution.
Extend the counter to other modulo ranges.
Implement the same design in other digital logic simulators like Logisim.

Simulation Instructions
Visit the Falstad Circuit Simulator.
Load the falstad_simulation.txt provided in this repository.
Observe the counter decrementing from 7 to 1.
Work on debugging or modifying the circuit to achieve the correct behavior of counting down from 6 to 0.

Feel free to fork this repository, clone it, or open an issue if you have suggestions or corrections. All contributions are welcome!
