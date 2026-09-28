# Logistics Data Science Project

## Project Overview
This project analyzes logistics shipment data to identify delivery delays, warehouse bottlenecks, and the impact of transport modes and shipment volume.

## Objectives
- Clean and validate shipment data
- Perform exploratory data analysis
- Calculate time spent at each logistics stage
- Identify warehouse bottlenecks
- Compare transport modes
- Analyze shipment volume and sorting time
- Train and evaluate a Random Forest model

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Dataset
The project uses a synthetic dataset containing 1,000 shipment records. It includes shipment origins, destinations, warehouses, timestamps, transport modes, delivery status, and shipment volume.

## Machine Learning
A Random Forest classifier is used to predict whether a shipment is delayed or on time. The model is evaluated using accuracy, precision, recall, F1-score, and ROC-AUC.

## Visualizations
1. Average delivery time by warehouse
2. Delivery time by transport mode
3. Shipment volume vs sorting time
4. Average time spent at each logistics stage

## How to Run
1. Download or clone this repository.
2. Install the required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open `logistics_analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run the notebook cells in order.

## Note
The dataset is synthetically generated for educational purposes and does not represent real company shipments.
