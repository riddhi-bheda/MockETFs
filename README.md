# Mock ETF Analysis and Visualization using Tableau

## Design  
This project uses multiple **Tableau dashboards** to analyze and visualize the **S&P 500** over time compared to a subset of **Fortune 500 companies**, representing a **mock exchange-traded fund (ETF)**. The dashboards incorporate various factors to filter and analyze ETF performance, including:  
- **Founder demographics**  
- **Company headquarters location**  
- **Employee satisfaction**  
- **Industry and sector classification**  

Each dashboard consistently includes two key graphs for comparison:  
1. **Line Graph**: Mock ETF vs. S&P 500 Price Over Time  
2. **Line Graph**: Mock ETF Returns vs. S&P 500 Returns Over Time  

Additional visualizations:  
- **Pie Charts**:  
   - CEO founder status (founder vs. non-founder)  
   - Gender distribution of CEOs (female vs. male)  
   - CEOs who lift weights  
- **Bar Charts**:  
   - Company Glassdoor ratings (distribution)  
   - Companies by industry and sector  
- **Map**:  
   - Company headquarters density by state  

---

## Strengths  
- **Unique Perspective**: Analyzes stock performance using **non-traditional factors** (e.g., leadership demographics, employee satisfaction).  
- **Interactive Dashboards**: Filtering one visualization dynamically updates others on the page.  
- **Alignment with Equity and Inclusivity**: Investigates leadership diversity, aligning with broader societal interests.  
- **Diverse Data Sources**: Combines datasets from **Kaggle, RPubs**, and hand-scraped Fortune 500 data for a holistic view.  
- **User-Friendly**: Well-organized dashboards with clear labels, interactive filters, and visually appealing design.  

---

## Challenges  
1. **Data Integration**:  
   - Original datasets lacked **company tickers**, complicating joins with the S&P 500 and Fortune 500 data.  
   - Employee satisfaction data was outdated (2023), requiring manual updates for 2024.  
2. **Mock ETF Calculations**: Implementing calculations in Tableau using filters was complex.  
3. **Economic Trends**: Drawing meaningful conclusions required addressing **confounding variables** with additional research.  

---

## Advice  
- **Think Outside the Box**: Use unconventional factors supported by **common sense** to analyze trends.  
- **Gain New Skills**: Experiment with unfamiliar tools (e.g., Tableau) for hands-on learning.  
- **Support with Data**: Leverage statistical techniques and visualizations to validate conclusions.  

---

## Public Dashboard Link  
[Explore the Tableau dashboard here](https://public.tableau.com/views/MockETFs_17345947737320/Dashboard5?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This repository includes the Tableau dashboard embed and resources to explore the **mock ETF analysis**.
