

🚗 AI Car Simulation using NEAT and Python

This project demonstrates an AI self-driving car simulation built using Python, Pygame, and the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.
The cars learn to drive automatically by evolving neural networks through generations.

⸻

📌 Project Overview

The goal of this project is to train an AI agent to drive a car around a track without crashing.
The car learns by using evolutionary neural networks provided by the NEAT library.

The AI improves over time through generations, learning how to avoid walls and navigate the track efficiently.

⸻

🧠 Technologies Used
	•	Python
	•	Pygame – for simulation and graphics
	•	NEAT-Python – for evolving neural networks
	•	NumPy (optional for calculations)

⸻

📂 Project Structure

ai-car-simulation/
│
├── main.py                # Main simulation script
├── config-feedforward.txt # NEAT configuration file
├── car.png                # Car image sprite
├── track.png              # Track map
├── README.md              # Project documentation


⸻

⚙️ Installation

1️⃣ Clone the Repository

git clone https://github.com/SURAJ587898/AISelfDrivingCar.git

2️⃣ Install Dependencies

pip install pygame
pip install neat-python
pip install numpy


⸻

▶️ Run the Simulation

Run the main file:

python main.py

The simulation will start and AI cars will begin learning to drive around the track.

⸻

🧬 How the AI Works
	1.	Each car is controlled by a neural network.
	2.	The network receives inputs from distance sensors.
	3.	Based on inputs, the network decides to:
	•	Turn left
	•	Turn right
	•	Move forward
	4.	Cars that survive longer receive higher fitness scores.
	5.	NEAT evolves better neural networks over generations.

⸻

📊 Features

✔ Self-learning AI cars
✔ Evolutionary neural network training
✔ Real-time simulation using Pygame
✔ Fitness-based genetic algorithm
✔ Visualization of AI learning process

⸻

🎯 Future Improvements
	•	Add multiple tracks
	•	Add speed control
	•	Save best trained model
	•	Add obstacle objects
	•	Improve sensors and physics

⸻

📸 Demo

You can visualize the cars learning in real-time during the simulation.



⸻

⭐ Support

If you like this project, please star the repository ⭐ on GitHub.

⸻

📜 License

This project is open-source and available under the MIT License.
:::
