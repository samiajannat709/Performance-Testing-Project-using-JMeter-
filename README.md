# 🚀 Performance Testing Project using Apache JMeter

## 📖 Overview

This project demonstrates performance testing using **Apache JMeter** to evaluate the performance, stability, and scalability of a web application under different user loads. It includes different types of performance testing, test plans, execution results, and an HTML dashboard report for analysis.

---

## 🌐 Base URL

```text
[https://your-base-url.com](https://restful-booker.herokuapp.com/apidoc/index.html)
```

---

## 🎯 Testing Types Covered

- Perform Load Testing
- Perform Stress Testing
- Perform Spike Testing
- Perform Volume Testing
- Perform Endurance (Soak) Testing

---

## 🛠️ Tools & Technologies

- Apache JMeter
- HTTP Request Sampler
- Thread Group
- HTTP Header Manager
- CSV Data Set Config (Optional)
- View Results Tree
- Summary Report
- Aggregate Report
- HTML Dashboard Report

---

## 📂 Project Structure

```text
Performance-Testing-Project/
│── Test_Plan.jmx
│── Test_Result.jtl
│── HTML_Report/
│── Screenshots/
│── README.md
```

---

## ⚙️ Test Configuration

- Number of Threads (Users): 50
- Ramp-Up Period: 10 Seconds
- Loop Count: 5
- Protocol: HTTP/HTTPS
- Request Method: GET

---

## 📊 Metrics Analyzed

- Response Time
- Average Response Time
- Minimum Response Time
- Maximum Response Time
- Throughput
- Error %
- Latency
- Active Threads

---

## 📷 Screenshots

### Test Plan

(Add Screenshot Here)

### Thread Group

(Add Screenshot Here)

### Summary Report

(Add Screenshot Here)

### Aggregate Report

(Add Screenshot Here)

### HTML Dashboard Report

(Add Screenshot Here)

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### 2. Open the Test Plan

- Launch **Apache JMeter**.
- Open the `Test_Plan.jmx` file.

### 3. Run the Test

- Click the **Start (▶️)** button in Apache JMeter.
- Wait until the test execution is completed.

### 4. Generate the HTML Report

```bash
jmeter -g Test_Result.jtl -o HTML_Report
```

### 5. View the Report

Open the following file in your browser:

```text
HTML_Report/index.html
```

---

## 📈 Project Features

- Simulates multiple virtual users
- Measures application response time
- Evaluates server performance under load
- Generates detailed HTML dashboard reports
- Analyzes throughput, latency, and error rate
- Identifies potential performance bottlenecks

---

## 👤 Author

**Jannatul Ferdous Samia**  
*SQA Learner*

---

## 📌 Note

This project was created for learning, practice, and portfolio purposes. It demonstrates performance testing using **Apache JMeter**, including **Load Testing**, **Stress Testing**, **Spike Testing**, **Volume Testing**, and **Endurance (Soak) Testing**. The project includes a JMeter test plan, execution results, and an HTML dashboard report to analyze application performance under different workloads.
