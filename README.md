# NBA Game Predictor: Advanced Machine Learning Model

## Overview
This project is an advanced NBA game prediction system that leverages historical data and daily updates to forecast game outcomes. It demonstrates proficiency in data science, machine learning, and sports analytics using Python.

## Features
- Custom data scraping and preprocessing of NBA game statistics
- Advanced feature engineering, including Elo ratings and rolling averages
- Multiple machine learning models:
  - Ridge Classifier
  - XGBoost
  - Neural Networks
- Comprehensive data visualization and model evaluation

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data](#data)
6. [Data Usage Disclaimer](#data-usage-disclaimer)
7. [Methodology](#methodology)
   - [Data Preprocessing](#data-preprocessing)
   - [Feature Engineering](#feature-engineering)
   - [Model Training](#model-training)
   - [Evaluation](#evaluation)
8. [Results](#results)
9. [Future Improvements](#future-improvements)
10. [Contributing](#contributing)
11. [License](#license)
12. [Contact](#contact)

## Installation
To set up this project, follow these steps:
1. Clone the repository:
```
git clone https://github.com/yourusername/nba-game-outcome-prediction.git
```
2. Navigate to the project directory:
```
cd nba-game-outcome-prediction
```
3. Install required packages:
```
pip install -r requirements.txt
```

## Usage
1. Ensure you have the latest data in the `Historical Data/` and `Daily Game Data/` folders Please note that scraping a large number of games can take several hours to comply with the website's rules.
2. Run the main Jupyter notebook:
```
jupyter notebook NBA_Game_Predictor.ipynb
```
3. Follow the notebook cells to train models and make predictions.

## Data
- Data Source: [Basketball Reference](https://www.basketball-reference.com/)
- The project includes scripts to scrape data from Basketball Reference
- Historical data: Comprehensive NBA game statistics from 2016 to present
- Daily data: Most recent game data, updated daily through web scraping

## Data Usage Disclaimer
This project uses data scraped from [Basketball Reference](https://www.basketball-reference.com/). While the scraping code is provided, users are responsible for reviewing and complying with Basketball Reference's terms of service before scraping or using any data. This project does not distribute any scraped data and is intended for educational and research purposes only.

## Methodology
1. Data Preprocessing: Cleaning and structuring raw NBA game data
2. Feature Engineering: 
- Calculating Elo ratings for teams
- Computing rolling averages for various statistics
- Generating team-specific and matchup-specific features
3. Model Training:
- Ridge Classifier for baseline performance
- XGBoost for handling complex feature interactions
- Neural Network for capturing non-linear patterns
4. Evaluation: Using metrics such as accuracy, precision, and ROC AUC

## Results
**Individual Model Performance**:
   - Ridge Classifier: 65.05% accuracy
   - XGBoost: 64.8% accuracy
   - Neural Network: 66.9% accuracy

## Future Improvements
- Incorporate player-level statistics and injury data
- Implement advanced ensemble techniques
- Develop a real-time prediction system with automated daily updates
- Create a web interface for easy access to predictions

## Contributing
Contributions to this project are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact
Berkhan Guzeller - berrkhanguzeller@gmail.com

Project Link: https://github.com/yourusername/nba-game-outcome-prediction

---
Created by Berkhan Guzeller | Istanbul Kultur University | Computer Science, 3rd Year
