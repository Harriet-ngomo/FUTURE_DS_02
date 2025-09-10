#  Facebook Ads Campaign Performance Analysis  
<img width="1101" height="500" alt="Screenshot 2025-09-10 000046" src="https://github.com/user-attachments/assets/8f81ec79-3e1a-49d6-91cc-a4538eb31295" />

Businesses invest heavily in social media ads but many struggle to answer critical questions:  

- Are campaigns really performing well?  
- Which ads drive the most engagement and conversions?  
- How effective is the spend in terms of CTR (Click-Through Rate) and ROI (Return on Investment)?  
- Where should the budget be reallocated for better results?  

This project analyzes **Facebook Ads data** to uncover insights and builds an **interactive Power BI dashboard** to visualize campaign performance 

---

##  Dataset  
- **Source**: [Kaggle – Facebook Ad Campaign Dataset](https://www.kaggle.com/datasets/madislemsalu/facebook-ad-campaign)  
- **Records**: 761 rows × 15 columns  
- **Key fields**: `impressions`, `clicks`, `spent`, `total_conversion`, `approved_conversion`  

---

##  Tools & Technologies  
- **Python (Pandas, Matplotlib, Seaborn)**: Data cleaning, EDA, metrics calculation  
- **Power BI** : Interactive dashboard creation  
- **Jupyter Notebook** : Exploratory analysis & visualization  

---

##  Project Workflow  
### 1. Data Cleaning & Preparation  
- Fixed **misaligned data** using Google Sheets  
- Converted **date fields** to `datetime` format  
- Handled **missing values** and removed **duplicates**  
- Created **new metrics**: CTR, CPC, CPA, ROI, Conversion Rate  


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

### JUPYTER NOTEBOOK VISUALS  

<p align="center"><b>DISTRIBUTION OF CTR ACROSS ADS</b></p>  
<p align="center">
  <img width="570" height="352" src="https://github.com/user-attachments/assets/88080e6e-5080-49ab-92e3-d992efbe1094" />
</p>  

<p align="center"><b>AVERAGE CPA BY GENDER</b></p>  
<p align="center">
  <img width="420" height="347" src="https://github.com/user-attachments/assets/2371d5a0-577d-4815-af13-e5d1c818a829" />
</p>  

<p align="center"><b>CTR VS ROI</b></p>  
<p align="center">
  <img width="530" height="402" src="https://github.com/user-attachments/assets/071072e4-33c2-4181-92da-63718970d833" />
</p>  

<p align="center"><b>AVERAGE CPA BY AGE GROUP</b></p>  
<p align="center">
  <img width="532" height="355" src="https://github.com/user-attachments/assets/110c34b5-1417-4a98-a06d-49cfc3faf13d" />
</p>  

<p align="center"><b>SPEND VS APPROVED CONVERSIONS</b></p>  
<p align="center">
  <img width="768" height="493" src="https://github.com/user-attachments/assets/1bc675ba-16d4-4187-9685-6c5b5d42cfd9" />
</p>  

<p align="center"><b>ROI BY GENDER</b></p>  
<p align="center">
  <img width="422" height="350" src="https://github.com/user-attachments/assets/86139177-317b-4480-a48b-241894e7bd7e" />
</p>  

<p align="center"><b>CTR BY AGE GROUP</b></p>  
<p align="center">
  <img width="546" height="363" src="https://github.com/user-attachments/assets/74aefa35-3519-4fd7-b6c7-cbd2ff5962eb" />
</p>  

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

## Conclusion  
The analysis highlights a clear gap between **reach and engagement**. While the campaign successfully delivered massive impressions, CTR remained poor limiting conversion efficiency. However, identifying **high-ROI ads** and **demographics with better performance** provides actionable direction for optimization  

This project demonstrates how **data-driven insights** can guide smarter ad spend, improve targeting and ultimately maximize campaign ROI 
---

##  Project Structure  
```bash
├── Data/
│   └── data.csv              
├── Images/                    
│   ├── insights.png          
│   ├── ctr_age.png             
│   ├── roi_ctr.png            
│   └── cpa_gender.png          
├── index.ipynb                
├── Facebook ads Report.pbix   
├── FinalData.csv             
└── README.md               
