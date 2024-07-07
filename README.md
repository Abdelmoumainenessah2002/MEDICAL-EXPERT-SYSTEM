# Medical Expert System

This is a Medical Expert System developed in Python using the `experta` library. It helps in diagnosing diseases based on the symptoms provided by the user.

## Table of Contents

- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [License](#license)

## Installation

To run this project, you need to have Python installed on your machine. Follow these steps to set up the project:

1. **Clone the repository:**

    git clone https://github.com/Abdelmoumainenessah2002/medical-expert-system.git
    
    cd medical-expert-system

2. **Create a virtual environment (optional but recommended):**

    python -m venv medical
    source medical/bin/activate  
    On Windows use `medical\Scripts\activate`


3. **Install the `experta` library:**

    pip install experta


## Project Structure

medical-expert-system/
├── Disease descriptions/
│ ├── Disease1.txt
│ ├── Disease2.txt
│ └── ...
├── Disease symptoms/
│ ├── Disease1.txt
│ ├── Disease2.txt
│ └── ...
├── Disease treatments/
│ ├── Disease1.txt
│ ├── Disease2.txt
│ └── ...
├── diseases.txt
└── medical_expert_system.py

- `Disease descriptions/`: Contains text files with descriptions of each disease.
- `Disease symptoms/`: Contains text files with symptoms of each disease.
- `Disease treatments/`: Contains text files with treatments of each disease.
- `diseases.txt`: A list of all diseases.
- `medical_expert_system.py`: The main Python script for the expert system.
- `requirements.txt`: The dependencies required for the project.

## Usage

To run the Medical Expert System, use the following command:

python medical_expert_system.py


Follow the on-screen instructions to enter your symptoms. The system will then diagnose the most probable disease and provide details and treatment options.

## License

This project is licensed under the MIT License.


Feel free to customize the content as needed, especially the `git clone` URL and any specific details about your project.

