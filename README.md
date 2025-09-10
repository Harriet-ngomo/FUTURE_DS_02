#  Facebook Ads Campaign Performance Analysis  

Businesses invest heavily in social media ads but many struggle to answer critical questions:  

- Are campaigns really performing well?  
- Which ads drive the most engagement and conversions?  
- How effective is the spend in terms of CTR (Click-Through Rate) and ROI (Return on Investment)?  
- Where should the budget be reallocated for better results?  

This project analyzes **Facebook Ads data** to uncover insights and builds an **interactive Power BI dashboard** to visualize campaign performance 

---

## 📂 Dataset  
- **Source**: [Kaggle – Facebook Ad Campaign Dataset](https://www.kaggle.com/datasets/madislemsalu/facebook-ad-campaign)  
- **Records**: 761 rows × 15 columns  
- **Key fields**: `impressions`, `clicks`, `spent`, `total_conversion`, `approved_conversion`  

---

##  Tools & Technologies  
- **Python (Pandas, Matplotlib, Seaborn)** → Data cleaning, EDA, metrics calculation  
- **Power BI** → Interactive dashboard creation  
- **Jupyter Notebook** → Exploratory analysis & visualization  

---

##  Project Workflow  
### 1. Data Cleaning & Preparation  
- Converted date fields → datetime  
- Handled missing values and duplicates  
- Created new metrics (CTR, CPC, CPA, ROI, Conversion Rate)  

### 2. Exploratory Data Analysis (EDA)  
- Summary statistics & distributions  
- Engagement analysis (clicks, impressions, conversions)  
- Performance by **age** and **gender**  

### 3. Dashboard Design (Power BI)  
- KPIs Overview (Impressions, Clicks, Spend, Conversions, CTR, ROI, CPA)  
- Engagement insights (Top ads by conversions & CTR)  
- Demographic performance (CTR by Age, ROI by Gender, CPA by Age)  
- ROI vs CTR scatter analysis  

---

##  Visuals  
### Power BI Dashboard  
 
<img width="1101" height="500" alt="Screenshot 2025-09-10 000046" src="https://github.com/user-attachments/assets/47accf11-f355-496c-a300-776f0a236487" />

### Jupyter Notebook Visuals  
<img width="570" height="352" alt="Screenshot 2025-09-10 000328" src="https://github.com/user-attachments/assets/88080e6e-5080-49ab-92e3-d992efbe1094" />
<img width="420" height="347" alt="Screenshot 2025-09-10 000351" src="https://github.com/user-attachments/assets/2371d5a0-577d-4815-af13-e5d1c818a829" />
<img width="530" height="402" alt="Screenshot 2025-09-10 000433" src="https://github.com/user-attachments/assets/071072e4-33c2-4181-92da-63718970d833" />
<img width="532" height="355" alt="Screenshot 2025-09-10 000512" src="https://github.com/user-attachments/assets/110c34b5-1417-4a98-a06d-49cfc3faf13d" />
<img width="768" height="493" alt="Screenshot 2025-09-10 000547" src="https://github.com/user-attachments/assets/1bc675ba-16d4-4187-9685-6c5b5d42cfd9" />
<img width="422" height="350" alt="Screenshot 2025-09-10 000612" src="https://github.com/user-attachments/assets/86139177-317b-4480-a48b-241894e7bd7e" />
<img width="546" height="363" alt="Screenshot 2025-09-10 000634" src="https://github.com/user-attachments/assets/74aefa35-3519-4fd7-b6c7-cbd2ff5962eb" />


---

## Key Insights  
- Campaign delivered **78M+ impressions**, **11K+ clicks**, and **585 conversions** 
- CTR was extremely low (**0.01%**), showing weak engagement despite high reach 
- Certain ads (like **1121206**) achieved exceptionally high ROI (~34x) with modest spend
- **Age 30–34** and **male users** delivered better ROI compared to other segments

---

##  Recommendations  
- Run **A/B testing** on creatives to improve CTR.  
- Reallocate budget toward **high-ROI ads & demographics**.  
- Optimize **landing pages** to reduce CPA.  
- Continuously track **CTR, CPC, and ROI** for real-time optimization.  

---

##  Project Structure  
```bash
├── Data/
│   └── data.csv               # Original dataset
├── Images/                    
│   ├── insights.png            # Power BI dashboard
│   ├── ctr_age.png             # Jupyter plot
│   ├── roi_ctr.png             # Jupyter plot
│   └── cpa_gender.png          # Jupyter plot
├── index.ipynb                # Jupyter Notebook (analysis & visuals)
├── Facebook ads Report.pbix    # Power BI file
├── FinalData.csv              # Processed dataset with new metrics
└── README.md                  # Project documentation
