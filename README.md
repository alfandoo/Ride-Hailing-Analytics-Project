# 🚗 Ride-Hailing Analytics Project  
## End-to-End Business Performance Analysis 

---

# 📌 Project Overview

Proyek ini merupakan end-to-end data analytics study pada dataset sintetis platform ride-hailing tahun 2024.  
Analisis dilakukan untuk mengubah data operasional menjadi insight strategis yang actionable bagi manajemen.

Fokus utama:
- 📊 Business Performance
- 👥 Customer & Driver Behavior
- 🚦 Operational Efficiency
- 💰 Revenue Optimization
- 🌍 Geographic Demand Pattern

---

# 1️⃣ Business Understanding

## 🎯 Problem Statement

Manajemen ingin memahami:

1. Seberapa sehat performa bisnis saat ini?
2. Apa penyebab utama pembatalan order?
3. Kapan dan di mana permintaan tertinggi terjadi?
4. Bagaimana meningkatkan revenue tanpa menurunkan kualitas layanan?

---

## 🎯 Business Objectives

- Menjaga completion rate > 90%
- Menekan cancellation rate
- Mengoptimalkan SLA (VTAT & CTAT)
- Mengidentifikasi peluang revenue growth
- Meningkatkan pengalaman customer & driver

---

# 2️⃣ Data Understanding

## 📂 Data Source

Dataset operasional ride-hailing tahun 2024 (synthetic production-ready warehouse schema), mencakup:

- Orders & Status
- Revenue & Payment Method
- Driver & Customer Ratings
- Pickup & Drop Location
- Distance & Delivery Time
- Vehicle Type

Data diproses menggunakan:
- Python (Pandas, Matplotlib, Seaborn)
---

# 📊 Executive Summary

## 💼 Business Performance

| Metric | Value | Insight |
|--------|-------|---------|
| Completion Rate | **90.04%** | Operasional stabil |
| Total Revenue | **Rp 6,323,866,900** | Monetisasi kuat |
| Avg Transaction | Rp 59,420 | Mid-range fare |
| Cancellation Rate | 9.96% | Perlu perbaikan |

---

## 👥 Customer & Driver Behavior

- Top Payment: **GoPay**
- Avg Driver Rating: 4.54 / 5
- Avg Customer Rating: 4.55 / 5
- Top Customer Cancellation: Berubah pikiran
- Top Driver Cancellation: Alasan pribadi pengemudi

Insight:
- Customer cancellation menunjukkan potensi masalah ETA / waiting time.
- Driver cancellation mengindikasikan supply reliability issue.

---

## 🚦 Operational Performance

| Metric | Value | Interpretation |
|--------|-------|---------------|
| Peak Hour | 07:00 | Morning commute |
| Busiest Day | Monday | Workday mobility |
| Avg VTAT | 6.3 min | Cukup baik |
| Avg CTAT | 40.6 min | Potensi inefficiency |
| Avg Distance | 10.81 km | Medium trip |

Insight:
CTAT relatif tinggi terhadap jarak tempuh → indikasi congestion atau route inefficiency.

---

## 🌍 Geographic & Vehicle Insights

- Dominant City: Jakarta
- Top Pickup: Margonda
- Top Drop: Botani Square
- Top Route: Tajur → Botani Square
- Top Revenue Vehicle: GrabCar

Insight:
Revenue sangat terkonsentrasi pada kota besar dan tipe kendaraan tertentu.

---

# 3️⃣ Data Preparation

Langkah yang dilakukan:

- Data cleaning & validation
- Timestamp transformation
- Feature engineering:
  - Hour extraction
  - Day of week
  - Weekend flag
  - Delivery duration (CTAT)
  - Assignment time (VTAT)
- Revenue aggregation
- Cancellation root cause analysis
- Route ranking
- SLA monitoring

---

# 4️⃣ Analytical Approach

Pendekatan analisis:

- Descriptive Analytics
- KPI Performance Analysis
- Behavioral Pattern Analysis
- SLA Monitoring
- Geographic Demand Mapping
- Revenue Segmentation by Vehicle

Fokus pada analytics layer (decision-support).

---

# 5️⃣ Key Business Insights

## 📊 Business Stability
Completion rate di atas 90% menunjukkan sistem stabil.  
Namun cancellation ~10% masih memiliki ruang perbaikan signifikan.

## 👥 Behavioral Risk
Customer cancellation dominan karena berubah pikiran.  
Driver cancellation dominan karena alasan pribadi.

## 🚦 Operational Bottleneck
Peak hour pukul 07:00 memerlukan supply planning khusus.  
CTAT relatif tinggi dibanding jarak tempuh.

## 💰 Revenue Concentration
Revenue sangat terpusat di Jakarta dan pada tipe kendaraan GrabCar.

---

# 6️⃣ Strategic Recommendations

## 📊 Business Strategy
- Implement dynamic surge pricing pada peak hour.
- Tambahkan driver incentive pada hari sibuk.
- Targeted campaign untuk slot non-peak.

## 👥 Customer Experience
- Tingkatkan akurasi ETA.
- Driver soft-skill training.
- Optimasi pickup location accuracy.

## 🚗 Operational Excellence
- Pre-position driver sebelum 07:00.
- Jadikan VTAT sebagai KPI utama.
- Optimasi rute dengan CTAT tinggi.

## 💰 Revenue Optimization
- Dorong pembayaran digital.
- Launch loyalty program.
- Corridor-based promotion untuk top routes.
- Diversifikasi revenue di luar Jakarta.

---

# 🎯 Conclusion

Platform berada dalam kondisi bisnis yang kuat dengan completion rate excellent dan revenue tinggi.

Prioritas strategis:
1. Pengurangan cancellation
2. Optimasi SLA
3. Diversifikasi revenue geografis

Proyek ini menunjukkan bagaimana data analytics dapat digunakan untuk mendukung strategic decision-making dan meningkatkan performa bisnis secara berkelanjutan.

---

## 👨‍💻 Author
Alfando – 2026
