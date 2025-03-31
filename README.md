# OPTIMISING MMWAVE RADAR DATA PROCESSING FOR IMPROVED HUMAN ACTION RECOGNITION


# **Human Action Recognition (HAR) using mmWave Radar**  

## **Overview**  
Human Action Recognition (HAR) is crucial in fields like **healthcare, fitness tracking, and security**. Traditional camera-based HAR systems raise **privacy concerns** and struggle in **uncontrolled environments**. This research focuses on leveraging **millimetre-wave (mmWave) radar** to enhance HAR accuracy, particularly for **low-intensity cardio exercises**.  

## **Approach**  
This project optimizes a **data processing pipeline** for mmWave radar-based HAR, using:  
- **Density-Based Spatial Clustering of Applications with Noise (DBSCAN):** For robust clustering of radar point clouds.  
- **Hungarian Algorithm:** For efficient data association across frames.  
- **Kalman Filtering:** For trajectory prediction and smoother motion tracking.  

By fine-tuning these algorithms, the pipeline effectively reduces noise, ensures **reliable feature extraction**, and maintains **consistent tracking**.  

## **Dataset: MiliPoint**  
The research is evaluated on the **MiliPoint dataset**, an extensive dataset designed for **HAR with mmWave radar**. The dataset provides high-resolution point cloud data for various human actions, enabling robust model training and validation.  

## **Results**  
- The optimized pipeline **outperforms baseline models**, achieving **up to 95.0% accuracy** with **PointNet++**.  
- Demonstrates the effectiveness of **mmWave radar for privacy-preserving HAR** applications.  
- Opens up new possibilities for **non-invasive activity monitoring in diverse environments**.  
Refer to paper - 


## **Technologies Used**  
- **Python**  
- **mmWave Radar Processing**  
- **Machine Learning & Deep Learning (PointNet++)**  
- **DBSCAN, Hungarian Algorithm, Kalman Filtering**  

## **How to Run**  : Refer to setup file 


## **Future Improvements**  
- Extend to **real-time HAR systems** using embedded devices.  
- Experiment with **transformer-based models** for improved performance.  
- Apply to broader HAR applications like **elderly fall detection**.  


This version is **polished for GitHub**, making it clear, professional, and easy to understand. Let me know if you need more refinements! 🚀
