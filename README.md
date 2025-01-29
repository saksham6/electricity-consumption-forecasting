# Electricity Consumption Forecasting

This project implements an Artificial Neural Network (ANN) to forecast electricity consumption based on historical data. The dataset used for training and evaluation is not included in the repository due to its large size, but it can be downloaded separately.

---

## Installation

### 1. Clone the Repository
To get started, clone the repository from GitHub:

```bash
git clone https://github.com/saksham6/electricity-consumption-forecasting.git
cd electricity-consumption-forecasting

```
## 2. Install Dependencies

### If a requirements.txt file is available, install dependencies using:

```bash
pip install -r requirements.txt

```

Alternatively, install required libraries manually:

```bash
pip install tensorflow==2.17.1 numpy==1.26.4 pandas==2.2.2 matplotlib==3.7.5 scikit-learn==1.2.2 pmdarima==2.0.4 statsmodels==0.14.4 holidays==0.63
```

### Running the Notebook

```bash
jupyter notebook

```
Then open Project_ANN_implementation.ipynb and execute the cells

Alternatetively 

``` bash
jupyter nbconvert --execute --to notebook --inplace Project_ANN_implementation.ipynb
```

## Dataset
The dataset used in this project is the Individual Household Electric Power Consumption Dataset, which is publicly available from the UCI Machine Learning Repository. Since the dataset is too large to be uploaded to GitHub, please download it manually from the following link:

🔗 [Download Dataset](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

## 3.Dataset Download Instructions
Visit the dataset link above.
Download the ZIP file containing the dataset.
Extract the data and place it inside the project directory (e.g., data/ folder).
Update the dataset path in the notebook if necessary.
2. Dataset Description
The dataset consists of electricity consumption measurements in a household over a period of four years. It includes attributes such as:

Date and Time
Global Active Power (kilowatts)
Global Reactive Power (kilowatts)
Voltage (volts)
Global Intensity (amperes)
Sub Metering (various household appliances)

## 4.Running the Notebook online
🔗 [Open Kaggle Notebook](https://www.kaggle.com/code/sakshamshah/notebook2265cbf93c/edit)

### **Steps to Run on Kaggle**
1. Click the link above.
2. If not logged in, sign in to Kaggle.
3. Click **"Copy & Edit"** to create your own editable version.
4. Click **"Run All"** to execute all cells.
