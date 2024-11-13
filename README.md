# Automatic Parking System Using Reinforcement Learning with Simulation in Unity

Welcome to the **Automatic Parking System** project! This repository showcases an autonomous vehicle parking solution, utilizing Reinforcement Learning (RL) and Genetic Algorithms (GA), and validated through simulation in Unity.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Simulation](#simulation)
- [Results](#results)
- [Challenges and Future Work](#challenges-and-future-work)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project aims to develop an autonomous parking system capable of performing various parking maneuvers like parallel, perpendicular, and angular parking. The system uses Reinforcement Learning to teach the agent optimal parking strategies in diverse urban scenarios.

**Project Objectives:**
- Develop a self-learning model for automated parking using RL.
- Test and validate the model in Unity for real-world applicability.

![Project Overview Image](path/to/overview-image.png)

---

## Features

- **Parking Strategy Optimization**: The RL model learns efficient paths for safe parking maneuvers.
- **Obstacle Avoidance**: Ensures the vehicle avoids nearby obstacles during parking.
- **Urban Environment Testing**: Validates the model’s effectiveness across various urban parking scenarios.

![Features Image](path/to/features-image.png)

---

## Technology Stack

- **Unity**: For creating and simulating complex parking environments.
- **Reinforcement Learning**: Trains the parking model to make efficient decisions.
- **Genetic Algorithms**: Optimizes model parameters for enhanced performance in challenging urban settings.
- **Python**: Used for the RL model and backend processing.

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Automatic_Parking_System_RL_Unity.git
   cd Automatic_Parking_System_RL_Unity
   ```

2. **Install Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup Unity Environment**
   - Download and install Unity (version X.X recommended).
   - Open the Unity project located in the `unity/` folder.

4. **Run the Simulation**
   - Configure and execute the Unity environment to start the simulation.

---

## Usage

1. **Configure the RL Model**: Adjust parameters in `config.py` to modify the training setup.
2. **Run Training**: Execute the RL training script:
   ```bash
   python train.py
   ```
3. **Visualize Results**: View results and improvements in Unity after each training session.

*Sample Command Execution*:

```bash
python train.py --episodes 5000 --learning_rate 0.01
```

---

## Simulation

The Unity simulation environment allows for testing in varied conditions, helping the RL agent to learn safe and efficient parking maneuvers.

![Simulation Environment GIF](path/to/simulation-gif.gif)

### Sample Video
Check out a video demo of the model in action below:

[![Watch the Demo Video](path/to/video-thumbnail.png)](path/to/demo-video.mp4)

---

## Results

After training, the model exhibits improved parking performance, achieving high success rates with reduced collision occurrences.

![Training Results Graph](path/to/results-graph.png)

- **Success Rate**: XX%
- **Average Time per Parking**: XX seconds
- **Collision Rate**: XX%

---

## Challenges and Future Work

### Challenges
- Adapting to varied parking scenarios with limited sensor data.
- Minimizing training time while achieving optimal performance.

### Future Work
- Integrate more complex scenarios, including moving obstacles.
- Implement in real-world test vehicles for practical assessment.

---

## Contributing

We welcome contributions to this project! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`feature/YourFeature`).
3. Commit your changes.
4. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Let us know if you have any questions or ideas for improvements! 😊

---
