## Car Price Prediction Web Application 🚗💰

This project is a **machine learning-powered web application** for predicting car prices based on various features like brand, year, mileage, engine specifications, and more. It uses **Streamlit** for the frontend and is implemented in Python.

---

## Screenshot 📸

![img alt](https://github.com/vinutmaradur/Car_Price_Predict/blob/main/car%201.png?raw=true)
![img_alt](https://github.com/vinutmaradur/Car_Price_Predict/blob/main/car%202.png?raw=true)
![img_alt](https://github.com/vinutmaradur/Car_Price_Predict/blob/main/car%203.png?raw=true)
![img_alt](https://github.com/vinutmaradur/Car_Price_Predict/blob/main/car%204.png?raw=true)

---

## Features 🎯

- **Interactive UI** for inputting car details such as brand, year of manufacture, mileage, etc.
- Predicts car prices using a **pre-trained machine learning model**.
- Includes dropdowns, sliders, and buttons for a user-friendly experience.
- Supports car brands, fuel types, and other categorical variables seamlessly.

---

## Cardetails.csv Dataset 📊

The Cardetails.csv file is a dataset containing comprehensive details about various cars, which is utilized for training the machine learning model and populating dropdown options in the web application.

# Key Features in the Dataset

# The dataset includes the following columns:

**1. name**:

- The brand or make of the car (e.g., Maruti, Hyundai, Honda).
- This is further processed to extract the brand name.

**2. year**:

- The year of manufacture of the car.
- Used to calculate the car's age.

**3. km_driven**:

- The total number of kilometers driven by the car.
- Helps estimate the wear and tear on the vehicle.

**4. fuel**:

- The type of fuel the car uses (e.g., Petrol, Diesel, LPG, CNG).

**5. seller_type**:

- Indicates whether the seller is an Individual, Dealer, or Trustmark Dealer.

**6. transmission**:

- Specifies whether the car has a Manual or Automatic transmission.

**7. owner**:

- The number of previous owners (e.g., First Owner, Second Owner, etc.).

**8. mileage**:

- The car's mileage in kilometers per liter (kmpl).

**9. engine**:

- The engine capacity of the car in cubic centimeters (cc).

**10. max_power**:

- The maximum power output of the car, usually in brake horsepower (bhp).

**11. seats**:

- The number of seats available in the car.

Sample Data

| name |	year | km_driven	| fuel | seller_type	| transmission	| owner	| mileage	| engine	| max_power	| seats |
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | 
| Maruti	| 2015 | 45000	| Petrol	| Dealer	| Manual	| First Owner	| 20	| 1200 | 85	| 5 |
| Hyundai |	2017 | 30000 |	Diesel |	Individual | Automatic | Second Owner	| 22	| 1400	| 100	| 5 |
| Honda	| 2019	| 20000 | CNG | Dealer	| Manual	| First Owner	| 18	| 1600 | 110 | 5 |

---

## Requirements 🛠️

Ensure you have the following installed:

- Python 3.7+
- Streamlit
- Pandas
- NumPy
- Pickle

---

## Installation and Setup 🚀

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```
   
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the model.pkl file (pre-trained ML model) and Cardetails.csv (dataset) in the project directory.

4. Run the application:
   ```bash
    streamlit run app.py
   ```

5. Open your browser and go to:
   ```bash
   http://localhost:8501
   ```

---

## Usage 💻
Select or input the car's details using the interactive widgets.
Click the "Predict" button.
The predicted car price will be displayed on the screen.

---

## File Structure 📂
- **app.py**: Main application script.
- **model.pkl**: Pre-trained machine learning model (required).
- **Cardetails.csv**: Dataset for car details (required).

---

## Example Input and Output 🔍
# Input
- **Car Brand**: Maruti
- **Year**: 2015
- **KMs Driven**: 45,000
- **Fuel Type**: Petrol
- **Seller Type**: Dealer
- **Transmission Type**: Manual
- **Owner**: First Owner
- **Mileage**: 20 kmpl
- **Engine**: 1200 cc
- **Max Power**: 85 bhp
- **Seats**: 5
# Output
- **Predicted Car Price**: ₹4,50,000

---

## Contributing 🤝
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## License 📄

This project is licensed under the MIT License.

---

## Acknowledgments 🙌
- Streamlit for providing an excellent framework for building interactive web applications.
- The dataset and machine learning model used for this project.

---

## Check my code 👁️
Below is the link to check my app

  [Project demo](https://carpricepredict-2025.streamlit.app/) 🚀

---

## Happy Coding! 💻✨

You can modify sections like the GitHub repository link or license if needed. Let me know if you'd like help adding anything else!
