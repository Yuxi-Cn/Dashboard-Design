# Dashboard Design

## Tableau Public
---
| Project           | Tableau Public Link                                                                                                                             |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| Bank Loan Analysis        | [Bank Loan Report](https://public.tableau.com/app/profile/yuxi.chen7353/viz/BankLoanReport-Dashboard/Summary)         |
| Electricity Analysis        | [GB Electricity Generation & Carbon Intensity](https://public.tableau.com/app/profile/yuxi.chen7353/viz/GBElectricityGenerationCarbonIntensity/GBGenerationDashboard) |

## Bank Loan Analysis
---

### Dashboard Overview:
This dashboard visualises data on bank loan report. The function board on the top displays: 
1. Total loan application
2. Total funded amount
3. Total amount received
4. Average interest rate
5. Average Debt-to-Income Ratio (DTI)

The dashboard consists of three pages: **Summary, Overview, and Details**.

#### 1. Summary

  - 1.1 Users can track percentage of good or bad loan issued along with related KPIs:
   
      -  Good / Bad Loan Application
      -  Good / Bad Loan Founded Amount
      -  Good / Bad Loan Amount Received
  
   - 1.2 Users can view KPIs for different loan statuses:
   
      - Charged off
      - Current
      - Fully Paid

#### 2. Overview
   - Users can gain a comprehensive understanding of loan application trends and relationships through the following visualisations:

      - Total Loan Application by Month - Area Chart
   
      - Total Loan Application by State - Map
   
      - Total Loan Application by Term (36 / 60 months) - Pie Chart
   
      - Total Loan Application by Employee Length - Bar Chart
   
      - Total Loan Application by Purpose - Bar Chart
   
      - Total Loan Application by Home Ownership - Tree Map

#### 3. Details
   - This table highlights key data points for users to track from the original dataset:

   | Id | Purpose | Home Ownership | Grade | Issue Date | Loan Amount | Interest Rate (Int Rate) | Installment | Total Payment |
   |----|---------|----------------|-------|------------|-------------|--------------------------|-------------|---------------|

> [!NOTE]
> This dashboard was developed to provide context-specific functional reports for bank managers while also serving as a learning tool for the dashboard design process.


## Electricity Analysis
---

### Dashboard Overview:

This Tableau dashboard presents data on electricity generation and carbon intensity in the Great Britain (GB) area. It offers interactivity in three key areas:

#### 1. **Periodic Generation Patterns:**
- Users can explore changes in total electricity generation patterns over various time periods:
   - Yearly
   - Quarterly
   - Monthly
   - Weekly
   - Daily

#### 2. **Map Visualisation Options:**
- Users can toggle between different map views to analyze data spatially:
   - Density Map
   - Filled Map

#### 3. **Calendar Selection:**
- Users can choose specific timeframes using the calendar option, with the format:
   - Month/Year (MM-YYYY)

> [!NOTE]
> This dashboard was created to provide a user-friendly interface for diverse audience while offering trend analysis for academic purposes.


### Data Source
---
The data is collected from two datasets: one from the ESO National Data Portal and the other from the UK government website. The links to these datasets are provided below, and the prepared data files are stored in the "Data Input" folder.

[Historic GB Generation Mix](https://www.nationalgrideso.com/data-portal/historic-generation-mix/historic_gb_generation_mix)

[UK Regional Carbon Dioxide Emissions](https://www.gov.uk/government/statistics/uk-local-authority-and-regional-carbon-dioxide-emissions-national-statistics-2005-to-2019)
