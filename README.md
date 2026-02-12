🌍 Exoplanet Habitability Prediction System

A Machine Learning–based system that predicts how suitable an exoplanet is for supporting life using real astronomical data from the NASA Exoplanet Archive and Kepler mission datasets.

The system generates:

✅ Habitability Score (0–100)

✅ Classification (Not / Possibly / Highly Habitable)

✅ Feature-based explanation

✅ Visual insights

🚀 Project Overview

This project analyzes planetary and stellar features such as:

Planet mass (pl_msinie, pl_masse)

Planet density (pl_dens)

Stellar radiation (pl_insol)

Equilibrium temperature (pl_eqt)

Star age (st_age)

Star luminosity (st_lum)

Orbital eccentricity (pl_orbeccen)

Using these features, a machine learning model predicts the probability that a planet may support life.

🛠️ Tech Stack
🔬 Machine Learning

Python

Scikit-learn

Pandas

NumPy

Matplotlib / Seaborn

🌐 Optional Frontend

React

Tailwind CSS

Chart.js / Recharts

📡 Data Source

NASA Exoplanet Archive

Kepler Space Telescope Dataset

⚙️ How It Works

Load Exoplanets.csv

Clean missing values

Select important habitability features

Scale/normalize data

Create habitability target column

Train ML model (Random Forest / Logistic Regression)

Predict probability

Convert to 0–100 habitability score

Classify planet

Explain prediction with feature importance

Visualize results

📊 Output Example
Habitability Score	Category
25	Not Habitable
58	Possibly Habitable
82	Highly Habitable
🧠 Machine Learning Approach

Supervised Learning

Train-Test Split (80/20)

Random Forest (Primary Model)

Evaluation using Accuracy, Precision, Recall

📈 Visualizations

Feature Importance Graph

Score Distribution Histogram

Scatter Plots (e.g., Insolation vs Temperature)

📂 Project Structure
Exoplanet-Habitability/
│
├── Exoplanets.csv
├── main.py
├── model_training.py
├── visualization.py
├── README.md
└── requirements.txt

▶️ How to Run

Clone the repository

git clone https://github.com/yourusername/Exoplanet-Habitability.git
cd Exoplanet-Habitability


Install dependencies

pip install -r requirements.txt


Run the project

python main.py
