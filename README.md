# Car-Price-Prediction

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)

## 📌1. Project Overview <a class="anchor" id="packages"></a>
This project explores and predicts the selling prices of used cars based on various factors like fuel type, transmission, ownership, seller type, and present market value. It blends **exploratory data analysis** with **machine learning models** to unearth pricing trends and forecast resale values.

## 2. Dataset <a class="anchor" id="dataset"></a>
The project uses a single dataset:

## Dataset Features

### 1. car_prediction_data

| **Columns**    | **Description**  |  
|--------------  |-----------------|  
| `Car_Name`     | Identify the brand or company name along with the specific model of each vehicle.|  
| `Year`         | Discover the manufacturing year of the vehicles, crucial for assessing depreciation and technology advancements. |  
| `Present_Price`| Current origin price of car |  
| `Selling_Price`| Selling price of car|  
| `Kms_Driven`   | Obtain the mileage of each vehicle, a key indicator of wear and tear and potential maintenance requirements.|  
| `rating`       | Average rating out of 10 for this anime. |  
| `Fuel_Type`    | Learn about the type of fuel the vehicles run on, whether it's petrol or diesel. | 
| `Seller_Type`  | Seller type weather dealer or individual| 
| `Transmission` |  Determine the transmission type, whether automatic, manual, or another variant.| 
| `Owner`        | How many owner of car (0, 1, 2, or 3)| 


## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2`, `Numpy 1.26` and `json `
+ `Matplotlib 3.8.4` and `seaborn `
+ `sklearn.model_selection` 
+ `scikit-learn all sklearn`
+ `html`
+ `scikeras`
+ `scipy`
+ `tensorflow`

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

---

## 🧑‍💻 Author

**Phillip Sethole**  
_Data Scientist, Intern @ ALX Africa_  
Built with ❤️, Python, and a dash of skepticism for overpriced hatchbacks.

---

## 📢 Final Word

This project shows how machine learning and EDA can not only predict a price — but **reveal the hidden gears** of a complex, value-driven market.

