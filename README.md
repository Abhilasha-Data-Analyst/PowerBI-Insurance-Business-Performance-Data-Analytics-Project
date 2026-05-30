## **🛡️ Shield Insurance Business Performance \& Customer Analytics**



## **1. About Project 📌**

Shield Insurance is an insurance company operating across major Indian cities and offering multiple insurance products through both online and offline sales channels.



This project analyzes business performance between November 2022 and April 2023 to understand:

* Customer growth
* Revenue trends
* Policy preferences
* Customer Demographic behavior
* Sales channel performance

The objective is to identify key business drivers, customer segments, and channel performance insights to support future growth strategies.



## **2. Project Domain**

Insurance Sector Analytics 



## **3. Dataset Information**

#### **Fact Tables**

* fact\_premiums- customer\_code, policy\_id, date, sales\_mode, final\_premium\_amt(INR)
* fact\_settlements- age, age\_group, settlement %



#### **Dimension Tables**

* dim\_customer- customer\_code, age, age\_group, city, date\_of\_birth
* dim\_policies- policy\_id, base\_coverage\_amt(INR), base\_premium\_amt(INR)
* dim\_sales\_mode- sales\_mode
* dim\_date- date, day\_type, mmm\_yy, week\_no
* dim\_age\_group- age\_group





## **4. Business Problem Statement**

Shield Insurance operates through multiple policies, cities, customer segments, and sales channels. The company needed business analysis to understand:

1. Which customer segments drive growth?
2. Which cities contribute maximum revenue?
3. Which policies perform best?
4. How customer behavior differs by age group?
5. Whether digital channels are replacing traditional sales methods?
6. How revenue and customer growth changed over time?



## **5. Business Area Covered**

1. Business Performance Analysis
2. Customer Demographics Analysis
3. Revenue Analytics
4. Policy Performance Analysis
5. Geographic Analysis
6. Sales Mode Analysis
7. Customer Growth Analysis
8. Monthly Trend Analysis



## **6. Business Metrics**

1. Total Revenue
2. Total Customer
3. Revenue by Age Group
4. Daily Customer Growth %
5. Daily Revenue Growth %
6. Monthly Customer Growth %
7. Monthly Revenue Growth %
8. Avg. Settlement %



## **7. Analysis Process**

1. Data Collection: Import insurance dataset into Power BI
2. Power Query ETL Transformation
3. Data Processing: Validation, Missing value checks, Data profiling, Promoted Header, Assign Data Type
4. Data Modeling: STAR Schema implementation
5. DAX Measures Creation: Dashboard Development, Data Visuals creation as per requirement
6. Business Storytelling \& Insight Generation
7. Stakeholder Reporting



## **8. Tools Used**

* **Excel** → Initial exploration \& validation
* **Power Query** → ETL \& transformation
* **Power BI** → Dashboard, DAX, Visualization
* **PowerPoint** → Business presentation \& reporting



## **9. Data Driven Insights**



### **📈 1. Strong Business Foundation with Rapid Growth**



* Shield Insurance built a strong market presence within six months.



* Key Metrics:

  1. Total Customers → 26,841
  2. Total Revenue → ₹989.25M
  3. Cities Covered → 5  (Mumbai, Delhi NCR, Hyderabad, Indore, and Chennai) 
  4. Insurance Products → 9 (POL4321HEL/POL4331HEL/POL3309HEL/POL5319HEL/POL6303HEL/POL6093HEL/POL9221HL/POL1048HEL/POL2005HEL)



* The company demonstrated strong customer acquisition and revenue generation capability during the growth period.



👉 **Business Insight:** Shield Insurance successfully established a scalable insurance business model across major urban markets.



### **👥 2. Middle-Age Customers Drive the Entire Business**



* Customer segmentation analysis showed that insurance demand is highly concentrated among middle-age customers.



* Largest customer segment: 

  1. Age Group:31–40 years
  2. Customers: 10,364
  3. Revenue contribution: ₹306.37M (30.97%)



* Second largest: 

  1. Age Group:41–50 years
  2. Customers: 6,159
  3. Revenue contribution: ₹229.68M (23.22%)



* Together, these two age groups (31–40 years \& 41–50 years) contributed more than half of total customers and revenue.



* Customer demand was highly concentrated among middle-age customers.



* Meanwhile:This segment remained significantly underpenetrated.

  1. Age Group: 18–24 Years
  2. Customers → 1,780
  3. Revenue → ₹24.27M



👉**Business Insight**: Insurance demand is strongest during life stages associated with career growth, family, financial responsibility, and asset protection. Middle-age customers contributed the majority of both customers and revenue.



👉**Business Opportunity**: Younger customers represent an untapped growth segment for future acquisition strategies.



## **💰 3. Revenue Concentration Shows Dependence on Core Segments**



* Revenue analysis revealed that business income is heavily dependent on a limited customer segment.



* Revenue distribution:

  1. Age Group:31–40 → ₹306.37M
  2. Age Group:41–50 → ₹229.68M
  3. Age Group:65+ → ₹206.22M



* Older customers (51+) generated strong revenue despite lower customer volume.



* This indicates:

  1. Higher policy value
  2. Greater insurance coverage
  3. Better claim engagement



👉**Business Insight:** Revenue is not equally distributed across customers. Older customer groups create higher customer lifetime value (CLV).



👉**Strategic Importance:** Retention of mature customer segments directly impacts revenue stability.



## **🏙️ 4. Delhi NCR Emerged as the Revenue Engine**



* Top Cities by Revenue

  1. Delhi NCR → ₹401.57M
  2. Mumbai → ₹239.51M
  3. Hyderabad → ₹160.52M



* Lowest Revenue Contribution

  1. Indore → ₹81.35M



* City-level analysis identified strong geographic concentration.

  1. Top city: Delhi NCR
  2. Customers: 11,007
  3. Revenue: ₹401.57M



* Followed by:

  1. Mumbai → ₹239.51M
  2. Hyderabad → ₹160.52M
  3. Indore generated the lowest contribution: ₹81.35M



* Delhi NCR alone contributed a major share of business revenue.



👉**Business Insight**: Urban markets remain the primary growth drivers because of higher purchasing power and insurance awareness.



👉**Risk Observation**: Heavy dependence on a few cities increases geographic concentration risk.



## **📈 5. March 2023 Became the Business Peak**



* Monthly trend analysis showed strong business acceleration during March 2023.



* Growth Metrics:

  1. Revenue growth: +85%
  2. Customer growth: +82.3%



* However, April showed immediate slowdown:

  1. Revenue Decline → (-41.7%)
  2. Customer Decline → (-41.4%)



* Growth pattern suggests a temporary event influence Possible reasons:

  1. Promotional campaigns
  2. Seasonal demand
  3. Sales push initiatives
  4. Customer acquisition programs



👉**Business Insight**: Business growth is highly campaign sensitive.



👉**Opportunity**: Understanding drivers behind March performance can help replicate future growth cycles.



## **🛡️ 6. Customer Preference Concentrated Around Few Policies**



* Policy demand analysis revealed uneven customer preference.



* Top policy: 

  1. POL4321HEL
  2. Customers: 4,434
  3. Policy wise customers by age group: **1**. 31–40 age group, **2.** followed by 25–30 age group **3.** and 18–24 customers age group



* Followed by(Other High-Performing Policies): POL3309HEL, POL4331HEL, POL5319HEL, POL6303HEL-Most policy buyers belonged to: 31–40 age group



* This indicates product-market alignment between middle-age customers and insurance offerings.



👉**Business Insight**: A small number of products drive majority demand.



👉**Business Risk:** Heavy dependency on few products increases concentration risk.



## **📋 7. Older Customers Show Better Settlement Performance**



* Settlement analysis revealed strong age-based differences.

  1. Highest settlement: Age Group:65+(74.22%), Age Group:51–65(65.35%)
  2. Lowest settlement: Age Group:18–24(37.51%)



* Settlement rates increased consistently with age, Possible reasons:

  1. Greater policy usage
  2. Higher claim activity
  3. Better product utilization



👉**Business Insight:** Older customers show stronger insurance engagement and value realization.



👉**Business Value:** These segments require stronger retention programs.



## **📲 8. Offline Agents Still Dominated Business Performance**



* Sales channel analysis showed clear dominance of Offline Agents.



* Offline Agent Performance:

  1. Customer contribution: 14,873 customers
  2. Share Contribution: 55.41%
  3. Revenue contribution: ₹550.76M (55.67%)



* Offline Agent generated more revenue than all other channels combined.



* Meanwhile: Digital Revenue:

  1. Online App → ₹160.97M
  2. Online Website → ₹124.62M



👉**Business Insight:** Customers still prefer human guidance while purchasing insurance products. Offline trust remains critical.



## 

## **🔄 9. Business is Gradually Moving Toward Digital Channels**



* Although Offline Agent dominates, digital growth signals are strong.



* Online Website Revenue Growth

  1. Initial → ₹2.09M
  2. Final → ₹45.98M



* Online App also showed continuous improvement



* At the same time Offline Direct Revenue Decline

  1. Initial → ₹39.84M
  2. Final → ₹10.01M 



* Customer preference is shifting toward digital experiences.



* Business transition observed**:** Traditional channels → Digital adoption



👉**Business Insight:** The company is entering digital transformation stage.



👉**Future Growth Driver:** Digital channels may become major contributors over time.



## **10. Project Outcome**



* **Key Outcomes**

  1. Total Customers Analyzed → 26,841
  2. Total Revenue Evaluated → ₹989.25M
  3. Highest Revenue Market → Delhi NCR (₹401.57M)
  4. Highest Revenue Segment → Age Group 31–40 (₹306.37M)
  5. Highest Performing Channel → Offline Agent (₹550.76M)
  6. High-performing policy → POL4321HEL
  7. Emerging opportunities identified: **1**.Digital channel growth, **2**.Younger customer acquisition, **3**.Geographic expansion



* Business Impact-The analysis helped identify:

  1. Major revenue-driving customer segments
  2. High-performing cities and policies
  3. Sales channel transformation trends
  4. Customer behavior patterns across demographics
  5. Digital growth opportunities



👉 The project provided actionable insights for customer targeting, revenue growth, and digital expansion strategies.





## **11. Business Recommendations**



### **📲 1. Accelerate Digital Transformation**



* Digital channels showed rapid growth.
* Recommended actions:

  1. Improve mobile app experience
  2. Strengthen website onboarding
  3. Simplify online policy purchase journey
  4. Launch digital awareness campaigns
* Expected impact: Higher scalability and lower acquisition costs.



### **👥 2. Build Age-Based Customer Strategy**



* **Current business depends heavily on**: 31–50 age customers
* **Recommended approach**:

  1. 31–50: Retention \& upsell campaigns
  2. 18–24: Awareness programs and starter plans
  3. 65+: Premium services and loyalty programs
* **Expected impact**: Balanced customer portfolio.



### **🌍 3. Expand High-Potential Markets**



* **Priority cities**:

  1. Delhi NCR
  2. Mumbai
  3. Hyderabad
* **Expansion opportunities**:

  1. Increase agent network
  2. Local marketing campaigns
  3. Region-specific products
* **Expected impact**: Revenue growth and market expansion.



### **🛡️ 4. Strengthen High-Performing Policies**



* **Focus products**: POL4321HEL, POL3309HEL, POL4331HEL
* **Recommended actions**:

  1. Bundle offerings
  2. Cross-selling campaigns
  3. Premium upgrades
* **Expected impact**: Higher customer lifetime value.



### **📈 5. Optimize Sales Channel Strategy**



* **Current state**: Offline Agent = strongest channel
* **Future trend**: Digital channels growing rapidly.
* **Recommended model**: Offline trust + Digital scale
* **Maintain**: Agent ecosystem
* **Grow**: App \& Website channels
* **Expected impact**: Balanced long-term growth strategy.

### 

### **12. Project Deliverables \& Resources**



#### 🔗 **Power BI Live Dashboard-**[**Link**](https://app.powerbi.com/view?r=eyJrIjoiNzUxMmRlNmQtNzQxZC00ZTY3LThlYTgtMGNjNWQ5NmFiZDk0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

###### 

#### **📊 Project Walkthrough Video**- **\[Watch Dashboard Demo](Dashboard/Dashboard.mp4)**



#### 📄 \[**Project Presentation]-(Presentation/Project\_Presentation.pdf)**



#### **🖼️ Presentation Preview-**





#### **Contact-**

Abhilasha- Data Analyst

📧 Email: connectspace.abhilasha@gmail.com



