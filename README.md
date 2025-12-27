# Morocco Rental Market Analysis | 2025

## Context

<p style="color: gray; font-size: 14px;">
Written and edited by: <strong>Salah Eddine YOUSFI</strong> — 27/12/2025
</p>


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






<p align="center">
  <img src="src/Median%20Rent%20Map%20by%20Region%20Morocco.jpg" width="700">
</p>

<p align="center">
  <img src="src/City%20Ranking%20by%20Average%20Rent%20Morocco.jpg" width="700">
</p>

<p align="center">
  <img src="src/Rental%20Price%20Distribution%20Morocco.jpg" width="700">
</p>

<p align="center">
  <img src="src/Rental%20Listings%20Concentration%20by%20Region.jpg" width="700">
</p>

<p align="center">
  <img src="src/Rental%20Price%20Variability%20by%20Region.jpg" width="700">
</p>

<p align="center">
  <img src="src/Marrakech%20Median%20Rent%20Spatial%20Distribution.jpg" width="700">
</p>

<p align="center">
  <img src="src/Average%20Rent%20by%20District%20Marrakech.jpg" width="700">
</p>

<p align="center">
  <img src="src/TOPSIS%20Tourism%20City%20Ranking%20Morocco.jpg" width="700">
</p>
