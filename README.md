# GQMLQO_notebooks
Space for executing notebooks from A-Practical-Guide-to-Quantum-Machine-Learning-and-Quantum-Optimization book

## Starting
1. Install python 3.9

sudo apt update
sudo apt install build-essential cmake

sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.9

2. Create python environment (with any name, here as an example \it qiskit_env)

python3.9 -m venv qiskit_env

2. Source this environment

source qiskit_env/bin/activate

3. install qiskit and other dependencies in the environment

pip install numpy cmake scikit-build
pip install qiskit==0.39.2 
pip install qiskit-aer==0.11.1
pip install pylatexenc==2.10
