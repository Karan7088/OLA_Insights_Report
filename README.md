🚖 OLA Ride Data Analytics Report
SQL | Data Analytics | Business Intelligence Project
📌 Project Overview

This project presents an in-depth analysis of OLA ride booking data to uncover insights related to ride demand, revenue performance, customer behavior, cancellation patterns, and operational efficiency.

The dataset was sourced from Kaggle, a widely used platform for data science and analytics datasets.

This project simulates real-world ride-hailing business intelligence analysis.

📂 Data Source

📊 Dataset: OLA Ride Booking Data

🌐 Source: Kaggle

📁 Format: CSV

🛢 Imported into: MySQL

🛢 Data Fetching Process
🔹 Step 1: Download Dataset from Kaggle

The dataset was downloaded from Kaggle and imported into the SQL database for structured analysis.

🔹 Step 2: Create Database
CREATE DATABASE ola_analysis;
USE ola_analysis;
🔹 Step 3: Create Table Structure
CREATE TABLE ola_rides (
    ride_id INT,
    booking_date DATE,
    customer_id INT,
    driver_id INT,
    vehicle_type VARCHAR(50),
    pickup_location VARCHAR(100),
    drop_location VARCHAR(100),
    ride_distance DECIMAL(10,2),
    ride_time INT,
    fare_amount DECIMAL(10,2),
    payment_method VARCHAR(50),
    ride_status VARCHAR(50),
    cancellation_reason VARCHAR(255)
);
🔹 Step 4: Fetch Data
SELECT * FROM ola_rides;
📊 Business Objectives

Analyze ride demand trends

Identify peak booking hours

Evaluate revenue performance

Understand customer cancellation behavior

Compare vehicle type performance

Optimize operational efficiency

