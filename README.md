# IPL Win Predictor

This repository contains code and documentation for an IPL Win Predictor, a machine learning model that predicts the win probability of a chasing team in Indian Premier League (IPL) matches after each over.

### Overview
The IPL Win Predictor utilizes historical IPL match data to calculate win probabilities for the chasing team based on factors such as runs scored, wickets fallen, and match status. The project aims to analyze and predict the likelihood of a team winning while chasing a target score.

### Table of Contents
- [Dependencies](#dependencies)
- [Setup](#setup)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

### Dependencies
The project requires the following dependencies:
- Python (version >= 3.x)
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ipl-win-predictor.git
   cd ipl-win-predictor
   ```
2. Create a virtual environment (recommended) and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Download or prepare IPL match data and place it in the `ipl_data` directory.

### Usage
Execute scripts or notebooks to preprocess data, train models, and generate win probabilities for IPL matches.

### Methodology
The methodology for the IPL Win Predictor involves:
- Data collection and preparation
- Data cleaning and feature engineering
- Model selection (Logistic Regression, RandomForestClassifier)
- Model training and evaluation
- Win probability calculation after every over during a match.

### Results
The project analyzes and presents win probabilities for specific IPL matches, showcasing the fluctuation of win probabilities as matches progress. Detailed results and conclusions are provided in the README.

### Contributing
Contributions are welcome! If you wish to contribute, please fork the repository, create a new branch, make your changes, and submit a pull request.

### License
This project is licensed under the [MIT License](LICENSE).
