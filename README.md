# Morocco Rental Market Analysis | 2025
> **Written and edited by:** Salah Eddine YOUSFI  
> **Date:** 27/12/2025


Do not hesitate to contact me through my LinkedIn profile  


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/salah-eddine-yousfi-b2532a375/)


## Context



This project focuses on the rental housing market in Morocco through the analysis of recent data, with the objective of comparing rental prices and market supply across cities and regions. The dataset corresponds to rental listings published in November 2025.

This project is conducted for personal and educational purposes only.

Initially, the goal was to construct a dataset by aggregating information from multiple rental platforms. However, due to access restrictions and platform usage policies, it was not possible to automatically collect data from several sources.

As a result, a single dataset was built using publicly available rental listings from Avito Morocco, relying on a web scraping approach. The collected data were then cleaned, filtered, and structured to enable reliable statistical analysis and visualization 📊.

---

## Origin of the Tourist City Ranking

At the end of the data visualization phase, the project naturally evolved toward proposing a ranking of Moroccan cities from a tourism perspective. However, a fundamental question quickly emerged: how can a city be objectively classified as tourist-oriented or not?

Describing a city as “very touristy” or “less touristy” without numerical evidence remains subjective and difficult to justify 🤔.  
An initial idea was to rely on qualitative labels such as average, good, or very good. However, this approach raises a critical issue: on what objective basis can such labels be assigned? Converting subjective judgments into arbitrary numerical values does not lead to a rigorous or credible analysis.

To overcome this limitation, the ranking was designed to rely exclusively on measurable and recognized indicators directly linked to tourism activity. In this context, quantitative data computed at the level of major provinces were integrated, including:

- the number of tourist overnight stays,
- the accommodation occupancy rate,
- and the rental price.

Taken together, these indicators provide a more accurate representation of the attractiveness of a city or province. Overnight stays and occupancy rates reflect actual tourist demand, while rental prices play a significant role in destination choice and affordability.

This reasoning forms the foundation of the multi-criteria approach adopted in the project, aiming to replace subjective assessments with an analysis grounded in concrete, data-driven evidence.

---

## Source and Relevance of Tourist Data

At present, official tourism data for the year 2025 are not yet available. Consequently, the tourism indicators used in this project cover the period from January to August 2024.

Despite this limitation, the data remain representative. Tourism activity between 2023 and 2024 shows an approximate increase of 7%, indicating a stable trend without major structural changes.

Furthermore, during the application of the TOPSIS multi-criteria decision-making method, several sensitivity analyses were conducted by modifying the weights assigned to each criterion. In all tested scenarios, the final ranking order remained unchanged, which confirms the robustness of the results and the reliability of the underlying data ✅.


Let’s dive into the visualizations and explore the main insights.



## Results Overview

---

## I. Exploratory Analysis and Data Visualization  


---

### 1. Regional Analysis of Median Rental Prices

<p align="center">
  <img src="src/Median%20Rent%20Map%20by%20Region%20Morocco.jpg" width="700">
</p>

- Highlights **regional disparities** in median rental prices  
- Higher rents observed in regions that are:
  - highly urbanized  
  - economically dynamic  
- Key indicator: **rental demand pressure**

---

### 2. Ranking of Major Cities by Average Rental Price

<p align="center">
  <img src="src/City%20Ranking%20by%20Average%20Rent%20Morocco.jpg" width="700">
</p>

- Comparative overview of major Moroccan cities  
- Higher average rents in cities that are:
  - coastal  
  - administrative centers  
  - major tourist hubs  
- **Methodological choice**:
  - cities with very few rental listings were excluded  
  - objective: ensure **statistical reliability and comparability**

---

### 3. Overall Distribution of Rental Prices

<p align="center">
  <img src="src/Rental%20Price%20Distribution%20Morocco.jpg" width="700">
</p>

- Rental market dominated by **mid-range prices**  
- Limited presence of a **high-end segment**  
- Asymmetric distribution:
  - justifies the use of the **median instead of the mean**  
  - reduces sensitivity to extreme values  

---

### 4. Geographic Concentration of Rental Listings

<p align="center">
  <img src="src/Rental%20Listings%20Concentration%20by%20Region.jpg" width="700">
</p>

- Identification of regions with **high listing density**  
- Strong correlation with:
  - economic attractiveness  
  - tourism intensity  
- Key indicator: **rental market activity**

---

### 5. Rental Price Variability Across Regions

<p align="center">
  <img src="src/Rental%20Price%20Variability%20by%20Region.jpg" width="700">
</p>

- Analysis of **price dispersion** across regions  
- High variability observed in:
  - tourist regions  
  - mixed residential–tourism markets  
- Key indicator: **market instability**

---

### 6. Spatial Structure of Rental Prices in Marrakech

<p align="center">
  <img src="src/Marrakech%20Median%20Rent%20Spatial%20Distribution.jpg" width="700">
</p>

- Strong **intra-urban heterogeneity**  
- Higher rents concentrated in:
  - central areas  
  - tourist-oriented districts  
- Clear **spatial segmentation** of the urban rental market  

---

### 7. Ranking of Marrakech Districts by Average Rent

<p align="center">
  <img src="src/Average%20Rent%20by%20District%20Marrakech.jpg" width="700">
</p>

- Hierarchical ranking of districts by average rent  
- Main explanatory factors:
  - location  
  - accessibility  
  - neighborhood standing  
- **Methodological choice**:
  - districts with very few listings were excluded  
  - objective: ensure **representative and robust results**

---

## II. Multi-Criteria Decision-Making Analysis (TOPSIS)

---

### 8. Tourist City Ranking Using the TOPSIS Method

<p align="center">
  <img src="src/TOPSIS%20Tourism%20City%20Ranking%20Morocco.jpg" width="700">
</p>

- **Decision-support analysis** based on multiple criteria:
  - median rental prices  
  - tourist overnight stays  
  - occupancy rates  
- Applied method: **TOPSIS**
  - evaluation relative to an **ideal** and an **anti-ideal** solution  
- Results:
  - identification of cities offering the **best overall compromise**  
- Validation:
  - sensitivity analysis on criterion weights  
  - stable ranking → **robust and reliable decision outcomes**






Please feel free to reach out to me through my LinkedIn Profile if you have any further questions or would like to discuss this study in more detail.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/salah-eddine-yousfi-b2532a375/)
