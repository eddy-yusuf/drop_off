# Drop-Off Zone Traffic Dynamics 

This repository documents the iterative development of a multi-car drop-off simulation in a school zone, created as part of the research project: **"Human–ChatGPT Co-Creation of Educational Simulations: A Case Study on Drop-Off Zone Traffic Dynamics" (2025)**.

It includes the complete codebase, detailed simulation logic, and all final outputs.  
The full simulation is designed to be executed in a **Jupyter Notebook**, using **Python (matplotlib + animation)**.

---
## Purpose of the Project

This project investigates how **ChatGPT** can assist human developers in co-creating an educational simulation that visualizes traffic flow and behavioral modeling of cars in a constrained school drop-off lane scenario.

We simulate the following:

- Multiple cars (up to 20 without live report; up to 10 with live report) approaching a designated drop-off point.
- Each car behaves based on acceleration, deceleration, and a set of **(randomized) safe following distance**.
- Cars independently **stop at the same drop-off line** for a fixed randomized time.
- The system avoids **collisions** and maintains realistic kinematic behavior.

---
## Project Structure

The code development is deployed in several key stages and each stage involves a number of iteration in the code development
- a single car simulating realistic kinematics as it approaches a drop-off line
- adding 2 - 5 cars in the simulation to create a stream of cars in the dynamics
- adding random stop duration and random
- increasing the number of cars up to 20
- adding random safe distance between cars
- adding live dashboard panel (position, speed, state, safe distance) but reducing the number of cars to 10

We organize the project into 2 folders: prompts and codes

folder prompts/
* stage 1 --> iteration1, iteration2, ....
* stage 2 --> iteration1, iteration2, ...
* etc

folder codess/
* stage 1 --> iteration1, iteration2, ....
* stage 2 --> iteration1, iteration2, ...
* etc
