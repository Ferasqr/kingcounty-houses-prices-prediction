# King County House Price Predictor
![CE200FDD-0ABD-46CF-8EF1-9F516276EACD](https://github.com/Ferasqr/kingcounty-houses-prices-prediction/assets/93034515/14d66af0-54f6-44a8-a28f-a85832a78667)

## Description
The King County House Price Predictor is a machine learning application designed to predict house prices in King County, Washington. This repository contains Jupyter Notebooks and necessary files for data cleaning, model training, and a GUI application for predicting house prices.

## Repository Structure
- **`Cleaning+Models.ipynb`**: This notebook includes the data cleaning process, exploratory data analysis, and model training. Various machine learning models are evaluated to find the best-performing one for house price prediction.
- **`Predictor_app.ipynb`**: This notebook contains the code for a graphical user interface (GUI) application. The application allows users to input house features and get a predicted price. It also includes features for mapping house locations and displaying tables of predicted prices for nearby houses.
- **`kingcounty_house_data.csv`**: The dataset containing house sales data from King County, which includes features like the number of bedrooms, bathrooms, square footage, etc.

## Features
- **Data Cleaning and Analysis**: Steps to clean the dataset and perform exploratory data analysis to understand key features influencing house prices.
- **Model Training**: Training and evaluation of multiple machine learning models including Linear Regression, Random Forest, and CatBoost Regressor to predict house prices.
- **GUI Application**: A user-friendly interface built with PySimpleGUI that allows users to input house details and get an instant price prediction. Additional features include mapping houses on a map and displaying detailed tables of nearby house prices.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Ferasqr/kingcounty-houses-prices-prediction.git
   cd kingcounty-houses-prices-prediction
   ```

2. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebooks or the GUI application:
   ```sh
   jupyter notebook Cleaning+Models.ipynb
   jupyter notebook Predictor_app.ipynb
   ```

## Usage
1. Open the `Cleaning+Models.ipynb` notebook to explore the data cleaning and model training process.
2. Open the `Predictor_app.ipynb` notebook to run the GUI application. Follow the instructions in the notebook to input house features and get a price prediction.

## Dataset
The dataset used in this project is the King County House Sales dataset, which includes house sale prices along with various features of the houses sold.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
