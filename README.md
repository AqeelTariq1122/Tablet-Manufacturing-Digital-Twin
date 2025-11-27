# 💊 Pharmaceutical Tablet Manufacturing Simulation (Digital Twin)

> **A 7-day manufacturing digital twin built in AnyLogic to detect bottlenecks, measure throughput, and test capacity improvements in tablet production.**

![Blue Doodle Project Presentation (1)](https://github.com/user-attachments/assets/a0c8a283-c085-4ab6-89c6-5f949a098ab9)


---

## 🧠 Project Overview
This simulation models a real manufacturing line for pharmaceutical tablets using **batch processing with queues at every station**. Raw material for **one batch arrives every 2 hours**, and each stage can process **only one batch at a time** while the rest wait in its queue.

| Station | Processing Time |
|---------|-----------------|
| Dispensing | 15 min |
| Blending | 30 min |
| Granulating | 1 hr |
| Drying | 2 hrs |
| Compression & Coating | 3 hrs |
| Packaging | 4 hrs |

---

## 🎯 Impact Highlights
> Accomplished bottleneck identification as measured by queue buildup (18/13/7 batches) by simulating a 7-day production run with single-item processing and station queues.

> Accomplished a 68.9% reduction in batch processing time as measured by average batch completion time (45 hrs → 14 hrs) by increasing capacity of Compression & Packaging from 1 to 2 units.

> Accomplished a 75% increase in total output as measured by total completed batches (40 → 70) by removing bottlenecks through targeted workstation duplication.


---

## 📊 Results

### 🟡 **Before Optimization (Original Line)**
| Station | Queue Size |
|---------|-----------|
| Compression & Coating | 18 |
| Packaging | 13 |
| Drying | 7 |

- **Avg. time to produce one batch:** 45 hours  
- **Total batches produced in 7 days:** 40  

### 🟢 **After Optimization (Added 2nd Machine at Compression & Packaging)**  
| Station | Queue Size |
|---------|------------|
| Compression & Coating | 0 |
| Packaging | 0 |
| Drying | 7 |

- **Avg. time to produce one batch:** 14 hours  
- **Total batches produced in 7 days:** 70  

---

## 📌 Key Insight
> 🔎 **Compression & Coating and Packaging are the critical bottlenecks that restrict production output.**  
📈 Doubling only these two stations eliminates waiting, greatly increases throughput, and drastically reduces batch completion time.

---

## 🛠️ Technologies Used
| Category | Tools |
|----------|------|
| Simulation | AnyLogic (DES), Queuing, Digital Twin Concepts |
| Analysis | Queue Metrics, Batch Timing, Throughput KPIs |
| Visualization | Real-time Animation & Experiment Dashboard |

---

## 🖥️ How to Run
1. Open the .alp file in AnyLogic.
2. Click Run to simulate the 7-day production.
3. Edit station capacities or processing times to test improvements.
4. Observe queues, batch completion time, and total output.

---

## 🏁 Conclusion
This digital twin proves that **strategic workstation scaling is more effective than changing all processes.**  
Increasing only **Compression & Coating + Packaging capacity** generates:

- ⏱️ **68.9% reduction** in time to produce a batch  
- 📦 **75% increase** in total batch output  
- 🚫 **Zero queues across all stations**

> 💡 *A small change in capacity can outperform complex process redesign.*

---

## 👨‍💻 About the Author

**Aqeel Tariq**  
Operations Analyst | Simulation Modeling & Data Visualization  
🔧 AnyLogic ▪ Python ▪ Java ▪ Streamlit  
📍 Building digital twins that turn complex operations into measurable decisions.

---

