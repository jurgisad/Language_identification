Language_Identification Project
This project, commissioned by Euromonitor, aims to develop a robust data pipeline to enhance the accuracy of scraped multilingual data.

### **Key Findings**

**The new method significantly improved accuracy:**

- **Lithuania**: from **81.4%** to **96%**  
- **Canada**: from **92.8%** to **98%**

**Most errors occurred in short texts**, especially **titles with international words**.

**Two country types identified for effective use:**
- **Monolingual**: one dominant language with minor international mix  
- **Multilingual**: no clear dominant language

**The method works fully automatically in 57.5% of cases** (~**193.8k** entries).

**42.5%** (~**143k** entries) **remain unresolved**, requiring **minimal human review at one stage** or **further analysis** in multilingual contexts.

**The pipeline uses a funnel-down approach**, where each stage incrementally refines the dataset, ultimately isolating a small subset of uncertain cases for which no automatic language label is assigned. **This minimizes false assumptions and ensures high confidence in labeled data.**




### **The methodology combines:**

Classic statistical techniques

Modern machine learning models

Rule-based logic

All methods applied were scientifically researched, and their theoretical justification can be found in the accompanying report. For full technical details of the proposed pipeline, refer to the PDF, section "Tiriamoji dalis – Siūlomas metodas" on page 22.


To get data to run the added notebooks, don't hesitate to reach out. Run each cell block one by one, it requires specific data structures that were present and a more in depth data wrangling approach will be soon added so you run this with your own data. As the data is confidential you will not get the same results as the data shared will be fictional. Feel free to improve the accuracy of the first run you get and let us know how to improve it further! 
