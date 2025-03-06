# Milk Quality Prediction

## Overview
This project is a **Milk Quality Prediction System** built using **Machine Learning** and deployed using **Streamlit**. The model predicts the quality of milk based on various input parameters like **pH level, Temperature, Taste, Odor, Fat content, Turbidity, and Color level**.

## Technologies Used
- **Python**
- **NumPy**
- **Pickle** (for model loading)
- **Streamlit** (for UI)
- **Scikit-learn** (for model training, not included in this script)

## Features
- User-friendly web interface using Streamlit
- Takes milk parameters as input
- Predicts the quality of milk: **Low, Medium, or High**
- Background image for a better UI experience

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/milk-quality-prediction.git
   cd milk-quality-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install numpy streamlit scikit-learn
   ```

3. Ensure that you have the trained model file `milk_model_1.sav` stored in the correct path (`C:/Users/hasee/Desktop/Ant/project/ML/milk_model_1.sav`). If not, modify the script to point to the correct model location.

4. Run the Streamlit app:
   ```bash
   streamlit run milk_quality_app.py
   ```

## How to Use
1. Open the web application.
2. Enter values for the required milk parameters:
   - **pH Level**
   - **Temperature**
   - **Taste Level**
   - **Odor Level**
   - **Fat Level**
   - **Turbidity**
   - **Color Level**
3. Click on the **Predict** button.
4. The app will display the predicted quality of the milk (Low, Medium, or High).

## Project Structure
```
├── milk_quality_app.py  # Main Python script with Streamlit UI
├── milk_model_1.sav     # Pre-trained ML model (required for predictions)
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

## Future Enhancements
- Improve the UI design for better user experience.
- Train and test multiple models to improve accuracy.
- Deploy on a cloud platform for broader accessibility.

## Author
**Dharun Ravanan**

## License
This project is licensed under the MIT License.

