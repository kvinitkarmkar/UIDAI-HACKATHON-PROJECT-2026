# Aadhaar Data Analytics & Policy Optimization

### **Project Overview**

This project focuses on the large-scale analysis of Aadhaar update trends across India. By applying advanced data cleaning and demographic profiling, we identified a massive **22.89% duplication rate** in raw data. The goal is to transition the current reactive update system into a proactive, **"Child-First"** policy framework that maximizes Government ROI.

---

### **🚀 Key Impact & Data Audit (Post-Cleaning)**

The data cleaning process was critical in identifying system inefficiencies:

* **Duplicate Elimination**: Successfully identified and purged **474,307 duplicate records**, representing **22.89%** of the raw dataset.
* **Database Optimization**: Reduced total population count by **25.8% (-1.26 Crore records)**, ensuring a verified unique user base.
* **Refined Demographics**: Corrected the **Youth-to-Child ratio from 9.14:1 to 10.90:1**, highlighting a dominant Adult (90.17%) update volume.
* **Entity Efficiency**: Achieved a **44.6% reduction** in unique entities, streamlining the reporting architecture.

---

### **📍 Infrastructure Priority: Critical Districts**

We identified "Hotspots" with the highest duplication counts, requiring immediate infrastructure upgrades:

1. **West Bengal - North 24 Parganas**: 6,870 duplicates
2. **Andhra Pradesh - East Godavari**: 6,438 duplicates
3. **West Bengal - Barddhaman**: 5,976 duplicates
4. **Maharashtra - Pune**: 5,632 duplicates

---

### **💡 Strategic Policy Recommendations**

#### **Strategy A: Infrastructure & Load Management (High-Volume)**

* **Target**: Central (9.9M), East (8.4M), and South (6.4M) regions.
* **Focus**: Expand **Aadhaar Seva Kendras (ASKs)** by 40-50% in states like **Uttar Pradesh (6.46M updates)** to prevent overcrowding.

#### **Strategy B: "Child-First" Policy (Low-Volume/Emerging)**

* **Target**: North, West, and Northeast regions.
* **Focus**: Increase the **Child Update Ratio (currently 9.8%)** through mandatory school-based enrollment camps.
* **Mandates**: Link Aadhaar updates to Class 10 & 12 Board Exam registrations.

---

### **💰 Economic Impact & ROI**

* **Subsidy Leakage Prevention**: Purging duplicates and ghost beneficiaries is projected to save **₹12,000 Cr/year**.
* **Operational Savings**: Decentralizing updates to school camps will reduce manual processing costs by **₹3,500 Cr/year**.
* **Overall Value Creation**: This framework offers a **36x Return on Investment (ROI)** over a 3-year period.

---

### **🛠 Tech Stack**

* **Language**: Python (Pandas, Matplotlib, Seaborn)
* **Analysis**: Geographic Mapping, De-duplication Algorithms, Demographic Profiling

---

### **⚙️ How to Run the Analysis**

Follow these steps to set up the environment and execute the data cleaning and visualization pipeline:

#### **1. Prerequisites**

Ensure you have **Python 3.10+** installed on your system.

#### **2. Clone the Repository**

```bash
git clone https://github.com/KVINITKARMKAR/UIDAI-HACKATHON-PROJECT-2026.git
cd UIDAI-HACKATHON-PROJECT-2026

```

#### **3. Install Dependencies**

Install the required Python libraries using the `requirements.txt` file:

```bash
pip install pandas matplotlib seaborn numpy

```

#### **4. Data Preparation**

* Place your raw Aadhaar dataset in the `Data/raw/` directory.
* Ensure the file is re-named `your_data.csv` (or update the path in the script).

#### **5. Execute the Analysis Pipeline**

Run the main script to perform data cleaning, de-duplication, and generate visualizations:


#### **6. View Results**

* **Cleaned Data**: The verified dataset (with **-25.8% records**) will be saved in `Data/processed/`.
* **Visualizations**: All charts (Regional Distribution, Top 10 States, and High Duplication Zones) will be available in the `visuals/charts` folder.

---

### **📁 Project Directory Structure**

```text
UIDAI-HACKATHON-PROJECT-2026/
├── Data/
│   ├── raw/            # Unprocessed data (49.2M records)
│   └── processed/      # Cleaned data (36.5M records)
├── notebooks/          # Jupyter notebooks for exploratory analysis
├── visuals/            # Exported PNGs (Charts & Dashboards)
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies

```

---

### **✅ Final Project Checklist**

* **Data Cleaning**: Handled **4.7 Lakh duplicates**.
* **Demographic Split**: Validated **90.2% Adult** vs **9.8% Child** ratio.
* **Priority Mapping**: Identified **Top 10 Districts** for infrastructure upgrades.
* **Policy Strategy**: Included the **"Child-First"** recommendation for 5 & 15-year biometric milestones.
