# Car Price Predictor ML Model

This repository contains a machine learning model for predicting car prices, implemented using Streamlit for a web-based user interface. Users can input various car attributes to get a price prediction based on a trained model.

## Project Overview

The car price prediction application allows users to input details about a car, such as its brand, year of manufacture, mileage, fuel type, and more, to predict its price. The model used for prediction is saved in a pickle file and is loaded into the Streamlit app.

## Features

- **User Input Form**: Users can select or input car details through a user-friendly form.
- **Price Prediction**: The model predicts the car's price based on the input data.
- **Interactive UI**: Built using Streamlit for an interactive web-based experience.

## Getting Started

### Prerequisites

1. **Python 3.7+**: Ensure you have Python 3.7 or later installed.
2. **Virtual Environment**: It is recommended to use a virtual environment.

### Installation

1. Clone the repository:

    ```sh
    https://github.com/RupenWorks/car-price-predictor/tree/main
    ```

2. Set up a virtual environment:

    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. Install the required packages:

    ```sh
    pip install streamlit
    pip install pandas
    pip install scikit-learn

    ```

4. Place your trained model file (`model.pkl`) and dataset file (`Cardetails.csv`) in the project directory.

### Running the Application

1. Start the Streamlit app:

    ```sh
    streamlit run app.py
    ```

2. Open the provided local URL in your web browser to interact with the app.

## Usage

- **Select Car Brand**: Choose the car brand from the dropdown menu.
- **Input Details**: Use sliders and dropdowns to input other car details.
- **Predict**: Click the "Predict" button to get the predicted price of the car.


## Acknowledgements

- [Streamlit](https://streamlit.io) for creating the interactive web framework.
- [Scikit-learn](https://scikit-learn.org) for the machine learning tools.

---

Feel free to customize this `README.md` file to better fit your project's specific details and requirements. Let me know if you need any adjustments or additional information!

