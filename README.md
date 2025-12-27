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

### 1. Regional Analysis of Median Rental Prices

<p align="center">
  <img src="src/Median%20Rent%20Map%20by%20Region%20Morocco.jpg" width="700">
</p>

- Mise en évidence de **fortes disparités régionales** des loyers médians  
- Loyers plus élevés dans les régions :
  - fortement urbanisées  
  - économiquement dynamiques  
- Indicateur clé : **pression de la demande locative**

---

### 2. Ranking of Major Cities by Average Rent

<p align="center">
  <img src="src/City%20Ranking%20by%20Average%20Rent%20Morocco.jpg" width="700">
</p>

- Comparaison des principales villes marocaines selon le prix moyen de location  
- Domination des villes :
  - côtières  
  - administratives  
  - à forte attractivité touristique  
- **Choix méthodologique** :
  - exclusion des villes avec très peu d’annonces  
  - objectif : garantir la **fiabilité statistique** et la comparabilité  

---

### 3. Overall Distribution of Rental Prices

<p align="center">
  <img src="src/Rental%20Price%20Distribution%20Morocco.jpg" width="700">
</p>

- Marché dominé par des **loyers intermédiaires**  
- Présence limitée d’un segment **haut de gamme**  
- Distribution asymétrique (queue à droite), justifiant :
  - l’usage de la **médiane** plutôt que la moyenne  
  - une meilleure robustesse face aux valeurs extrêmes  

---

### 4. Geographic Concentration of Rental Listings

<p align="center">
  <img src="src/Rental%20Listings%20Concentration%20by%20Region.jpg" width="700">
</p>

- Identification des régions à **forte densité d’annonces locatives**  
- Corrélation marquée avec :
  - l’attractivité économique  
  - le dynamisme touristique  
- Indicateur clé : **intensité du marché locatif**

---

### 5. Rental Price Variability Across Regions

<p align="center">
  <img src="src/Rental%20Price%20Variability%20by%20Region.jpg" width="700">
</p>

- Analyse de la **dispersion des loyers** par région  
- Forte variabilité observée dans :
  - les régions touristiques  
  - les marchés mixtes (résidentiel + touristique)  
- Indicateur clé : **instabilité et volatilité des prix**

---

### 6. Spatial Structure of Rental Prices in Marrakech

<p align="center">
  <img src="src/Marrakech%20Median%20Rent%20Spatial%20Distribution.jpg" width="700">
</p>

- Forte **hétérogénéité intra-urbaine** des loyers  
- Loyers plus élevés dans :
  - les zones centrales  
  - les quartiers à vocation touristique  
- Mise en évidence d’une **segmentation spatiale claire** du marché urbain  

---

### 7. Ranking of Marrakech Districts by Average Rent

<p align="center">
  <img src="src/Average%20Rent%20by%20District%20Marrakech.jpg" width="700">
</p>

- Hiérarchisation des quartiers selon le prix moyen de location  
- Facteurs explicatifs principaux :
  - localisation  
  - accessibilité  
  - standing urbain  
- **Choix méthodologique** :
  - exclusion des quartiers avec un nombre très faible d’annonces  
  - objectif : résultats **représentatifs et robustes**

---

### 8. Tourist City Ranking Using the TOPSIS Method

<p align="center">
  <img src="src/TOPSIS%20Tourism%20City%20Ranking%20Morocco.jpg" width="700">
</p>

- Approche **multicritère** intégrant :
  - prix de location  
  - nuitées touristiques  
  - taux d’occupation  
- Méthode appliquée : **TOPSIS**
  - comparaison à une solution idéale et anti-idéale  
- Résultats :
  - identification des villes offrant le **meilleur compromis**  
- Validation :
  - tests de sensibilité sur les pondérations  
  - classement stable → **robustesse confirmée**








Please feel free to reach out to me through my LinkedIn Profile if you have any further questions or would like to discuss this study in more detail.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/salah-eddine-yousfi-b2532a375/)
