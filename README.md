# 🌦️ Weather Data Processing using Hadoop Ecosystem

A Big Data project that processes weather datasets using the Hadoop ecosystem. The project demonstrates a complete data pipeline from data storage and cleaning to distributed processing and visualization.

## 📌 Project Overview

This project aims to analyze weather datasets using distributed computing technologies. The workflow includes:

- Collecting and preprocessing weather data
- Containerizing the environment using Docker
- Storing data in HDFS
- Cleaning and querying data with Hive
- Processing data using MapReduce
- Visualizing the final results with Python

---

## 🛠️ Technologies Used

- Docker
- Hadoop
- HDFS
- Hive
- Java (MapReduce)
- Python
- Git & GitHub

---

## 📂 Project Workflow

### 1. Data Collection & Preprocessing
- Collect weather datasets.
- Clean missing and inconsistent values.
- Prepare the data for distributed processing.

### 2. Docker Containerization
- Build a Docker image containing:
  - Ubuntu
  - Hadoop
  - Hive
- Run the entire Big Data environment inside a Docker container.

### 3. Data Storage
- Upload raw datasets to HDFS.
- Create directories for raw and cleaned data.

### 4. Data Processing

#### Hive
- Create external tables.
- Clean and transform raw weather data.
- Store cleaned data back into HDFS.

#### MapReduce
- Implement Mapper, Reducer, and Driver classes.
- Calculate the highest temperature for each month.
- Generate distributed processing results.

### 5. Data Visualization
- Analyze processed data.
- Visualize weather trends using Python.

---

## 📁 Project Structure

```
├── Dockerfile
├── datasets/
├── hive/
│   └── queries.sql
├── mapreduce/
│   ├── Mapper.java
│   ├── Reducer.java
│   └── Driver.java
├── visualization/
│   └── analysis.py
├── report/
│   └── Final_Report.pdf
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Build the Docker image

```bash
docker build -t weather-project .
```

3. Run the Docker container

```bash
docker run -it weather-project
```

4. Start Hadoop services.

5. Upload datasets to HDFS.

6. Execute Hive queries.

7. Compile and run the MapReduce job.

8. Run the Python visualization script.

---

## 📊 Output

The MapReduce job calculates:

- Highest temperature recorded for each month.

The processed results are then visualized to identify weather trends.

---

## 👥 Team Members

- Habiba Yehia Shaaban
- Habiba Hamdy Ali
- Loubid Emad Mohamed
- Marwan Mohamed Zein
- Huda Ali Fouad Mohamed
- Rahma Mohamed Abdo

---

## 🎓 Course

**Distributed Processing**  
Faculty of Computer and Data Science  
Alexandria University  
2024–2025

---

## 📄 License

This project was developed for educational purposes as part of the Distributed Processing course.