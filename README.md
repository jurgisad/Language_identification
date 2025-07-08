# Language_Identification Project

This project, commissioned by **Euromonitor**, aims to develop a robust data pipeline to enhance the accuracy of scraped **multilingual data**.

---

### 🔍 **Key Findings**

**The new method significantly improved accuracy:**
- **Lithuania**: from **81.4%** to **96%**
- **Canada**: from **92.8%** to **98%**

**Most errors occurred in short texts**, especially **titles with international words**.

**Two country types identified for effective use:**
- **Monolingual**: one dominant language with minor international mix  
- **Multilingual**: no clear dominant language

**The method works fully automatically in 57.5% of cases** (~**193.8k** entries).  
**42.5%** (~**143k** entries) **remain unresolved**, requiring **minimal human review** or **further analysis**, especially in multilingual contexts.

**The pipeline uses a funnel-down approach**, where each stage incrementally refines the dataset, ultimately isolating a small subset of uncertain cases for which no automatic language label is assigned.  
This approach **minimizes false assumptions** and ensures **high confidence in labeled data**.

---

### ⚙️ **Methodology**

The proposed solution combines:
- ✅ **Classic statistical techniques**
- 🤖 **Modern machine learning models**
- 🧠 **Rule-based logic**

All methods are **scientifically grounded**, and detailed explanations can be found in the accompanying report.  
See the **PDF**, section **"Tiriamoji dalis – Siūlomas metodas"**, **page 22** for the full technical breakdown.

---

### 📂 **Running the Notebooks**

To run the included notebooks:
- Please reach out to receive example data.  
- Run each cell **step by step** – the pipeline expects specific data structures.  
- A full data wrangling guide will be added soon, so you can adapt the pipeline to your own datasets.  
- Note: due to confidentiality, **shared data will be fictional**, and results will differ from production.

We welcome your feedback! Feel free to suggest improvements or share ways to boost accuracy in the initial run.

---

📬 **Contact** us if you'd like to test this pipeline on your own data.

