
---

# Car Price Predictor

Welcome to the Car Price Predictor project! This application uses machine learning to estimate the market price of a car based on various user inputs. It features a user-friendly web interface built with Flask and Streamlit, and leverages the Random Forest algorithm to provide accurate price predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)


## Project Overview

The Car Price Predictor application allows users to input details about their vehicle and receive an estimated market price. The model predicts the price based on factors such as car company, model, year of purchase, fuel type, and kilometers driven.

## Features

- **User-Friendly Interface**: Interactive and easy-to-use web application.
- **High Accuracy**: Achieved a 91% R² score with the Random Forest model.
- **Custom Inputs**: Users can specify car company, model, year, fuel type, and mileage for tailored predictions.
- **Web Application**: Developed using Flask and Streamlit for a seamless experience.

## Technology Stack

- **Machine Learning**: Python, Random Forest, Pandas, NumPy
- **Web Development**: Flask, Streamlit
- **Data Visualization**: Matplotlib, Seaborn

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Hercules96/Car-Price-Prediction.git
   cd Car-Price-Prediction
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Open the Application**:
   - Navigate to `http://localhost:8501` in your web browser to access the Car Price Predictor.

2. **Input Car Details**:
   - Select the car company, model, year of purchase, fuel type, and enter the number of kilometers driven.

3. **Get Prediction**:
   - Click the "Predict" button to see the estimated price of your car.

## Results

The Random Forest model has been optimized to provide a high level of accuracy with a 91% R² score. This ensures reliable predictions based on the provided input data.

## Contributing

We welcome contributions to enhance the project! To contribute:

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes** and **Commit**:
   ```bash
   git commit -am 'Add new feature'
   ```
4. **Push to Your Fork**:
   ```bash
   git push origin feature/YourFeature
   ```
5. **Create a Pull Request**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out to:

- **GitHub**: [Hercules96](https://github.com/Hercules96)
- **Email**: [abhinav.bhardwaj900@gmail.com](mailto:abhinav.bhardwaj900@gmail.com)

---


