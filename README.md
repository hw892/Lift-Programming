# Lift Control System

This project is a group assessment for the **ECM 1414 module** at the University of Exeter. It involves designing and implementing an efficient lift (elevator) control system using queues, priority queues, and scheduling algorithms such as SCAN and LOOK. The system simulates real-time scenarios to minimize passenger wait times and optimize lift movements.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Simulation Details](#simulation-details)
- [Testing and Results](#testing-and-results)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
Efficient lift systems are critical in multi-story buildings. This project implements:
- Real-time request handling.
- Scheduling algorithms for optimized operations.
- Visualizations of performance metrics.

Optional enhancements include multiple-lift handling and a GUI visualization.

---

## Features
- **Data Structures**: Implemented queues, priority queues (using heaps), and scheduling algorithms.
- **Scheduling Algorithms**:
  - **SCAN**: Moves the lift in one direction until the end before reversing.
  - **LOOK**: Changes direction dynamically if no requests remain in the current direction.
- **Simulation**:
  - Configurable number of floors and passengers.
  - Handles real-time requests, lift capacity, and travel constraints.
- **Performance Metrics**:
  - Compare algorithms via charts and statistics.

---

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
1. **Run the simulation**:
   ```bash
   python main.py
   ```
2. Configure simulation parameters (e.g., number of floors, passengers) in `config.py`.

---

## Project Structure
```
/StudentID
│
├── specification
│   ├── coursework_spec.pdf
│   └── additional_docs/
│
├── sources
│   ├── main.py         # Main simulation driver
│   ├── lift_system.py  # Core lift logic and data structures
│   ├── algorithms.py   # SCAN, LOOK, and other algorithms
│   ├── utils.py        # Helper functions
│   └── config.py       # Simulation parameters
│
├── presentation
│   └── presentation_link.txt
│
├── results
│   ├── simulation_report.pdf
│   ├── charts/
│   └── data/
│
└── README.md
```

---

## Simulation Details
The simulation models the following:
- **Lift Operations**: Handles requests dynamically and prioritizes based on proximity and wait time.
- **Constraints**:
  - Configurable lift capacity.
  - Time taken to move between floors.

Charts and logs are generated to compare algorithm performance under various scenarios.

---

## Testing and Results
1. Test scenarios are defined in `config.py`.
2. Results are saved in the `results/` folder:
   - Performance charts.
   - Summary report.
3. Analyze results for:
   - Wait times.
   - Energy efficiency.

---

## Contributing
- Ensure your contributions align with the project's objectives.
- Follow the University's academic integrity policies.
- For any contributions, include detailed comments and disclosures in your code.

---

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

---

### Note
This project adheres to the University's guidelines on Generative AI usage. Prompts and AI contributions must be documented in `coursework_spec.pdf`. Ensure all work is properly cited to avoid plagiarism.
