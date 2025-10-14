# LEGO Set Investment : A Two-Part Analytical Approach
<img width="800" height="400" alt="UYYY" src="https://github.com/user-attachments/assets/67dd9a3d-ee9b-4b07-9841-a34a4a00eecd" />

*Figure: Sample LEGO bricks.*

## Overview
This project takes a comprehensive approach to LEGO set valuation through two distinct analytical lenses: descriptive analysis of historical patterns and predictive modeling of fair market prices. Using 2018-2019 LEGO set data, we answer both "what has happened" and "what should happen" to guide investment decisions.

## Business Problem
- LEGO sets can appreciate after retirement, but predicting winners is challenging
- Investors need both historical context AND forward-looking price guidance
- This project delivers both: market intelligence + predictive signals

## Part 1: Descriptive Analysis - Understanding the LEGO Market Landscape
**Goal:** Identify historical patterns, theme performance, and value indicators across the LEGO ecosystem.

**Methods & Findings:**
- **Theme Distribution Analysis:** Mapped set concentration across themes (Star Wars, City, etc.)
- **Value Efficiency Metrics:** Calculated price-per-brick ratios across categories
- **Pricing Pattern Recognition:** Identified licensing premiums and theme-specific pricing strategies

**Key Insights:**
- Largest themes don't guarantee best value-per-brick
- *Architecture* and *Creator Expert* themes show superior piece efficiency
- Licensed themes command price premiums beyond raw material value
<img width="600" height="300" alt="Screenshot 2025-10-14 at 15 56 45" src="https://github.com/user-attachments/assets/6263e972-d05d-4bd3-a52f-bd7cc24c938e" />

*Figure: Average price per brick (USD) by theme, showing which themes offer the best value.*

## Part 2: Predictive Modeling - Estimating Fair Market Value
**Goal:** Build machine learning models to predict what LEGO sets *should* cost based on their attributes.

**Technical Approach:**
- **Algorithms:** Linear Regression (baseline) vs. Random Forest (advanced)
- **Features:** Piece count, weight, theme, price category, licensing status
- **Validation:** Cross-validation, holdout testing, R² > 0.95 accuracy

**Business Application:**
- Identifies undervalued sets (retail price < predicted fair price)
- Flags overpriced sets for risk avoidance
- Provides quantitative foundation for investment decisions
<img width="600" height="300" alt="Screenshot 2025-10-14 at 15 58 00" src="https://github.com/user-attachments/assets/76deef03-622e-4a63-ab68-d6ad10b2b1a4" />

*Figure: Scatter plot comparing predicted vs actual retail prices. Points closer to the diagonal line indicate stronger model accuracy.*

## How the Two Parts Work Together
The descriptive analysis informs *which types* of sets to consider, while the predictive modeling identifies *specific sets* within those categories that represent good value.

**Example Workflow:**
1. **Descriptive Filter:** Focus on *Creator Expert* themes (based on Part 1 findings)
2. **Predictive Screen:** Identify which *Creator Expert* sets are undervalued (using Part 2 model)
3. **Investment Decision:** Target the intersection of promising themes + undervalued sets

## Tools & Methodology
- **Descriptive Analytics:** Pandas, NumPy, Matplotlib/Seaborn for EDA and visualization
- **Predictive Modeling:** Scikit-learn for machine learning, statistical validation
- **Business Intelligence:** Translating technical findings into actionable investment themes

  ## Business Value & Impact
- **Part 1 Value:** Strategic market understanding and theme selection framework
- **Part 2 Value:** Tactical set-specific valuation and pricing signals  
- **Combined Value:** Comprehensive analytical approach from market-level to asset-specific
- **Scalable Solution:** Transforms raw product data into actionable investment signals—reduces guesswork and can be adapted to other collectible markets

## Assumptions & Limitations
- **Data source:** LEGO product data for years 2018–2019 (publicly available listings).  
- **Assumptions:** We assume listed retail prices are valid and representative, and do not adjust for inflation.  
- **Limitations:** The model does not consider secondary/auction pricing behavior, rarity, condition, or external market trends.  
- **Caution:** Predictions are estimates; observed values may deviate due to design, packaging, scarcity, or collector demand.
 
 ## Next Steps  
- Expand dataset (more years, resale / auction data)   
- Adapt to other collectible markets  
- Develop interactive dashboard to allow users to explore predictions
- Incorporate time-series analysis for price appreciation trends

## Author
Akram Mohammed  
[![Email](https://img.shields.io/badge/Email-akrammohammed09@gmail.com-blue?style=flat&logo=gmail)](mailto:akrammohammed09@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/akram-mohammed-465052134)
