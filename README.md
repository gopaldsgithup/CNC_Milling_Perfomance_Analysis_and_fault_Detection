CNC Milling Performance Analysis and Fault Detection


📌 Overview
This project focuses on analyzing CNC milling machine performance and detecting faults using deep learning techniques. The primary objective is to predict tool wear condition, machining finalization status, and passed visual inspection using time-series sensor data collected from CNC milling experiments. The project includes data collection, preprocessing, deep learning model training (LSTM), and deployment via Streamlit.



📂 Project Structure



CNC-Milling-Performance-Analysis-and-Fault-Detection/
│
├── Data Collection & Preprocessing
│   ├── Merging experiment files
│   ├── Handling missing values
│   ├── Encoding categorical features
│   ├── Standardizing numerical features
│
├── Model Development
│   ├── LSTM-based deep learning model
│   ├── Multi-output classification
│   ├── Model training & evaluation
│   ├── Saving trained model & preprocessing objects
│
├── Deployment
│   ├── Streamlit-based web application
│   ├── Background image integration
│   ├── File upload functionality
│   ├── Model inference & results visualization


📊 Data Processing


Data Source: CNC milling sensor data from multiple experiment files.
Preprocessing Steps:
Merging experiment files with train data
Handling missing values (replacing with default values)
Encoding categorical features (Label Encoding)
Standardizing numerical features (using StandardScaler)
Reshaping data for LSTM (time-series input format)
