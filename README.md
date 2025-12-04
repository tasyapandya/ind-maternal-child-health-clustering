# Clustering-Based Profiling of Provincial Maternal and Child Health Indicators in Indonesia

This repository contains a data-driven analysis of maternal and child health patterns across Indonesian provinces using unsupervised learning. The goal is to identify province-level health profiles, uncover underlying patterns, and support evidence-based insights using DHS (Demographic and Health Survey) data from 2002–2017.

---

## 📌 Project Overview
Maternal and child health indicators vary significantly across Indonesian regions. Through clustering analysis, this project aims to:

- Build a **province-year panel dataset** of health indicators  
- Perform **feature engineering** for maternal, child, and birth-related variables  
- Explore multi-year patterns (2002, 2007, 2012, 2017)  
- Identify clusters representing meaningful health profiles  
- Interpret cluster characteristics for policy insights  

This repository is currently in early development (initial structure + preprocessing pipeline).

## 📊 Indicators Included
Key maternal–child health indicators engineered in this project:

### **Maternal**
- ANC 4+ visits (%)
- Skilled birth attendance (%)
- Facility delivery (%)
- Insurance coverage (%)
- Risky maternal age (%)
- Low education (%)

### **Child**
- Low birth weight (%)
- Full immunization (%)
- PNC any (%)  
- PNC within 48h (%)

### **Fertility Behavior**
- Average parity  
- Short birth interval (%)

### **Contextual & Demographic**
- Urban share (%)
- Province name & region  
- DHS survey year  

---

## 🧪 Methods (Planned)
### **1. Preprocessing**
- Harmonize variables across survey years  
- Clean and map province codes to BPS province names  
- Aggregate individual-level data to **province-year**  

### **2. Feature Engineering**
- Ratio-based indicators  
- Handling missingness  
- Scaling & normalization  

### **3. Clustering Experiments**
- **K-Means** (baseline)  
- **Hierarchical clustering** (Ward)  
- **GMM** (optional)  
- PCA for dimensionality reduction & visualization  
- Cluster stability checks  

### **4. Validation**
- Internal metrics:  
  - Silhouette score  
  - Davies–Bouldin index  
- External qualitative validation using IMR / SDGI benchmarks  
---

## 📝 Notes
Raw DHS microdata is **not included** in this repo due to data usage restrictions. Only derivative indicators and aggregated outputs will be shared.

---

For inquiries or collaboration, feel free to reach out.

