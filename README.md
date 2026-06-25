# Intel Data Center Energy Analytics (Tableau)

An interactive Tableau analysis of U.S. regional energy generation, demand, and renewable energy mix — built to answer a real business question: **where should Intel build its next data center?**

🔗 **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Intel-Data-Center-Energy-Analytics/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## Project Objective

Using regional hourly energy generation and demand data, this project evaluates which U.S. region offers the most reliable and sustainable power supply for siting a new data center — balancing energy surplus, grid stability, and renewable energy usage.

---

## Methodology

- Connected to regional hourly energy generation/demand data (wide and long-format datasets, the latter broken out by energy source)
- Built calculated fields: **Net Production**, **Renewable Energy / Renewable Energy Percentage**, **Percent Difference**
- Added an interactive **Select Period** parameter for filtering by time window
- Designed 6 linked dashboard views to compare regions on net production, renewable mix, and intraday supply/demand patterns
- Converted all data sources to extracts for performance and to enable Tableau Public publishing

---

## Key Findings

- **MIDA, SW, CENT, and SE** are net energy producers — generation exceeds demand in these regions
- The **Mid-Atlantic's** largest energy surplus occurs in **July**
- Top 3 regions by renewable energy percentage: **NW** (hydropower), **CENT** (wind), **CAL** (solar)
- **CENT** is the only region that is both a net producer *and* in the top 5 for renewable generation
- **California's** wind generation peaks in the afternoon, roughly 12 PM–9 PM, cresting around 3–4 PM

---

## Recommendation

**The Central (CENT) region is the recommended site for Intel's next data center.** It balances energy surplus, grid stability, and renewable energy usage better than alternatives like the Mid-Atlantic (heavy reliance on fossil fuels) or California (strong solar, but an overall energy deficit).

---

## Dashboard Views

**Main Dashboard**
![Final Intel Dashboard](Dashboard%20Screenshots/Final_Intel_Dashboard.png)

**Energy Source by Region**
*Breakdown of energy mix by source for each region.*
![Energy Source By Region](Dashboard%20Screenshots/Energy_Source_By_Region.png)

**Net Production**
*Net production (surplus vs. deficit) by region — identifies which regions are net producers.*
![Net Production](Dashboard%20Screenshots/Net_Production.png)

**Renewable Energy as % of Overall**
*Renewable energy's share of total generation by region.*
![Renewable Energy as Percent of Overall](Dashboard%20Screenshots/Renewable_Energy_as%25_of_overall.png)

**Renewable Energy Per Hour in California**
*Hourly renewable generation pattern in California, highlighting solar/wind peak hours.*
![Renewable Energy Per Hour in California](Dashboard%20Screenshots/Renewable_Energy_Per_Hour_in_Cal.png)

**Supply and Demand by Region (24h)**
*24-hour supply vs. demand curve, by region.*
![Supply and Demand by Region Over 24 Hours](Dashboard%20Screenshots/Supply_and_Demand%20_by_Region_Over24h.png)

**Hourly Difference in Generation**
*Hour-by-hour difference between generation and demand.*
![Hourly Difference in Generation](Dashboard%20Screenshots/Hourly_Difference_in_generation.png)

**Utility Power Source Breakdown**
*Utility-level breakdown of power source mix.*
![Utility Power Source Breakdown](Dashboard%20Screenshots/Utility_Power_Source_Breakdown.png)

---

## Tools & Techniques

- Tableau (calculated fields, parameters, interactive multi-view dashboard)
- Data extracts (.hyper) for performance and public sharing

---

## Why This Project

Demonstrates the ability to translate a business question into a structured data analysis — using interactive visualization to surface a clear, defensible recommendation, mirroring real-world analyst workflows.
