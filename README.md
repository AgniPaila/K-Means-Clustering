# K-Means Clustering Algorithm - (Java, Python)

## 📌 Project Description

This project implements a clustering program using the **K-Means algorithm** in Java. The goal is to cluster 1200 data points into `M` clusters, with values of `M` ranging from 3 to 12.

## 📁 Project Structure

The implementation consists of the following classes:

### 1. `KMeans`
- Main class containing the execution logic.
- Handles all K-Means algorithm steps:
  - Initialization
  - Point assignment
  - Cluster center update
  - Termination based on movement threshold

### 2. `Cluster`
- Represents a single cluster.
- Stores:
  - Assigned points
  - Cluster center
  - Cluster ID

### 3. `PointOfCluster`
- Represents a 2D data point `[x1, x2]`.
- Points are imported from a `.csv` file (`data.csv`).

## 📊 Execution Details
The clustering program is executed for M = 3, 6, 9, 12.

For each M, the program runs 15 times.

The clustering error (sum of squared distances) is computed for each run.

The run with the lowest clustering error is selected as the final solution.

- At termination, the following info is printed for each cluster:
  - Cluster ID
  - Final center coordinates (x1, x2)
  - Number of assigned points

## 📈 Output & Visualization
### Files Generated:
.csv files for:
- Points of each cluster
- Cluster centers

### Visualization:
A Python script is used to visualize:
- Points (+) colored by cluster
- Centers (*) in black

## 🚀How to Run
Compile the Java files using: javac *.java

Run the simulation using: java KMeans

## 📘 Course Info
- **Course:** Υπολογιστική Νοημοσύνη (Computational Intelligence)
- **Team:** This project was implemented in collaboration with one other student.
