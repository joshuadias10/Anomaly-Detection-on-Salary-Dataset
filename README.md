# **Anomaly Detection using KMeans and KNN**

## **Overview**
This project demonstrates an anomaly detection process using two techniques: 
- **KMeans Clustering** 
- **KNN (K-Nearest Neighbors)** from the **pyOD** library.

We use a synthetic dataset of salary data generated using the **Faker** library to detect outliers and anomalies in the salary distribution.

## **Dataset**
The dataset contains:
- 100 fake names generated by Faker.
- Corresponding randomly generated salaries.
- Two abnormal values added manually for anomaly detection.

## **Steps**
1. **Data Generation**: Using Faker and numpy to create random names and salary data.
2. **Data Visualization**: Displaying the salary distribution using boxplot and histogram.
3. **KMeans Clustering**: Clustering the salary data to visualize groupings and potential anomalies.
4. **Outlier Detection with KNN**: Utilizing the pyOD library to detect anomalies and identify outliers in the salary data.

## **Libraries Used**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Faker**
- **sklearn** (KMeans)
- **pyOD** (KNN)

## **Conclusion**
KMeans clustering provides a visual representation of clusters, while KNN helps in identifying potential anomalies in the dataset, showcasing how these methods can be effective in detecting abnormal data points.
