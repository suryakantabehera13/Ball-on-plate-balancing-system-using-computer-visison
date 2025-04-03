**Overview:**

The Ball-on-Plate Balancing System is a control system project that stabilizes a ball on a plate using actuators and feedback control. This project involves real-time ball tracking, simulation, and implementation of control strategies.

**Features:**

3D Model: Designed using Autodesk Fusion for visualization and mechanical analysis.
Real-Time Ball Tracking: Implemented using Python and OpenCV with the Circular Hough Transform algorithm.
Controller Design: Simulink-based controllers for stability and performance tuning.
Data Processing: Includes video/image data for training and testing.
Results & Analysis: Performance plots and research papers documenting the findings.

**Repository Structure:**

├── 3D model/                  # CAD models for the BnP system
├── controller_simulink_files/  # Simulink models for controller implementation
├── controller_plots/           # Performance plots of controllers
├── image_data/                 # Image datasets used for tracking and analysis
├── papers/                     # Research papers related to the project
├── results/                    # Experimental results and findings
├── video_data/                 # Recorded test videos of the system
├── .gitignore                  # Git ignore file
├── bnp.py                      # Main script for the BnP system
├── bnp_controller.py           # Controller implementation in Python
└── README.md                   # Project documentation

**Getting Started**

**Prerequisites:**

Python 3.x
OpenCV
NumPy
MATLAB/Simulink (for controller simulation)
Arduino IDE (for hardware implementation)

**Installation:**
1. Clone the repository:
    git clone https://github.com/suryakantabehera13/BnP-Balancing-System.git
2. Install dependencies:
    pip install -r requirements.txt
3. Run the main script:
    python bnp.py

**Control Strategies:**

PID Control: Classical feedback control for stability.
Model Predictive Control (MPC): Implemented in MATLAB/Simulink for improved disturbance rejection.
Kalman Filtering: Used for noise reduction in ball position tracking.

**Future Work:**

Hardware implementation with Arduino and servomotors.
Improved tracking algorithms using deep learning.
Integration of RL-based control.

**Contributing:**

Feel free to submit issues, pull requests, or suggestions to improve this project!
