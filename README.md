# ✈️ BlazeDemo Performance Testing Project

## 📌 Overview

This repository contains my **Individual Performance Testing Project** completed during my training at the **Information Technology Institute (ITI)**.

The project focuses on evaluating the performance, scalability, and stability of the **BlazeDemo Flight Booking Application** under different workload scenarios using **Apache JMeter**.

---

## 🎯 Project Objectives

- Design a reusable JMeter performance testing framework.
- Simulate real user behavior.
- Evaluate application performance under different workloads.
- Identify performance bottlenecks.
- Analyze key performance metrics.
- Provide optimization recommendations.

---

## 🛠️ Tools & Technologies

- Apache JMeter
- BlazeMeter Chrome Extension (Scenario Recording)
- Git & GitHub

---

## 📂 Project Structure

```
Blasedemo_Booking/
│
├── src/
│   └── blasedemobooking.jmx
│
├── Reports/
│   ├── Load/
│   ├── Stress/
│   └── Spike/
│
├── Presentation/
│   └── BlazeDemoBooking Performance Overview.pdf
│
│
└── README.md
```

---

## ⚙️ Test Workflow

The testing workflow simulates a complete booking process:

1. Open Website
2. Choose Departure & Destination
3. Select Flight
4. Complete Passenger Details
5. Confirm Booking

---

## 🧪 Test Scenarios

### ✅ Load Test

- 100 Virtual Users
- Ramp-Up: 25 Seconds
- Simulates normal user traffic

---

### ✅ Stress Test

- 500 Virtual Users
- Ramp-Up: 25 Seconds
- Evaluates system behavior under high load

---

### ✅ Spike Test

- 300 Virtual Users
- Ramp-Up: 1 Second
- Simulates sudden traffic spikes

---

## 📊 Performance Metrics

The following metrics were analyzed:

- Response Time
- Latency
- Throughput
- Error Rate
- Percentiles
- Transactions per Second

---

## 📈 Test Results Summary

| Test | Users | Errors | Avg Response |
|-------|------:|-------:|-------------:|
| Load | 100 | 0 | 497 ms |
| Stress | 500 | 0 | 634 ms |
| Spike | 300 | 71 | 2519 ms |

---

## 🔍 Key Findings

✔ The application remained stable during **Load Testing**.

✔ The application successfully handled **Stress Testing** without failures.

✔ The **Spike Test** exposed a bottleneck on the Landing Page when a sudden increase in concurrent users occurred.

---

## 🚀 Performance Improvement Recommendations

- Enable caching for static resources.
- Optimize server connection handling.
- Configure load balancing.
- Implement production auto-scaling.
- Monitor server resources continuously.
- Optimize connection pools.

---


## 👨‍💻 Author

**Mahmoud Abdella Ashri**

---

## 🙏 Acknowledgment

Special thanks to my instructors and mentors at the **Information Technology Institute (ITI)** for their guidance and continuous support throughout this project.