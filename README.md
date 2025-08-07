# Planar Data Classification with One Hidden Layer

This repository contains an implementation of a two‐layer neural network (one hidden layer) to classify planar (flower-shaped) data, as featured in Andrew Ng’s Neural Networks course on Coursera.

## 📂 Repository Structure

planar‐data‐classification/
│
├─ data/
│ └─ planar_utils.py # helper functions to load & visualize the dataset
│
├─ model/
│ └─ planar_nn.py # core neural network functions:
│ • initialize_parameters
│ • forward_propagation
│ • compute_cost
│ • backward_propagation
│ • update_parameters
│ • predict
│
├─ notebooks/
│ └─ planar_classification.ipynb
│ • interactive walkthrough
│ • decision boundary plots
│
├─ results/
│ └─ figures/
│ └─ decision_boundary.png
│
├─ requirements.txt # Python dependencies
├─ README.md # this file
└─ .gitignore

bash
Copy
Edit

## 🚀 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/planar-data-classification.git
   cd planar-data-classification
Create a virtual environment & install dependencies

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate     # on Windows: venv\Scripts\activate
pip install -r requirements.txt
Run the notebook
Launch Jupyter and open the interactive walkthrough:

bash
Copy
Edit
jupyter notebook notebooks/planar_classification.ipynb
Train your model

Adjust the hidden layer size, learning rate, and number of iterations in the notebook or planar_nn.py.

Re-run cells to see how decision boundaries change.

📈 Results
After training, you’ll find example decision boundary plots in the results/figures/ folder. Feel free to tweak hyperparameters to observe under-/over-fitting behavior.
