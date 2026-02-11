# Deforestation Analysis – Moreno Department (Santiago del Estero, Argentina)

This project analyzes deforestation patterns in the Moreno department (Santiago del Estero Province) in relation to socioeconomic conditions and the land-use categories defined by the Native Forest Territorial Planning (OTBN).

Santiago del Estero recorded the highest rate of deforestation in the region during 2007–2008 (Ginzburg & Torrella, 2022), a period in which Provincial Law 6,942 on land use planning was enacted. Although this regulation classifies native forests into conservation categories, deforestation processes continue.

The study evaluates forest loss alongside social vulnerability indicators, represented by the percentage of population with Unmet Basic Needs (NBI).

---

## Project Overview

The objective of this analysis is to examine:

- The spatial distribution of deforestation  
- The OTBN conservation categories (I, II, III)  
- The socioeconomic context (NBI percentage)  
- The relationship between forest loss and social inequality  

The Moreno department was selected due to its large deforested area and high levels of social vulnerability (Aguiar et al., 2016; Schmidt et al., 2022).

---

## Data

- High-resolution global maps of 21st-century forest cover change (Hansen et al., 2013)  
  https://data.globalforestwatch.org/documents/52d6787146ee47b8b742f3e99a3a2276/about  
- OTBN shapefile  
- Census and socioeconomic data (NBI indicator)  
- Official cartography (Instituto Geográfico Nacional)

---

## Methodology

The workflow included:

1. Compilation of forest cover change datasets  
2. Integration of OTBN conservation categories  
3. Spatial overlay analysis  
4. Calculation of deforested area by category  
5. Analysis of census tracts and NBI percentage  
6. Cartographic production and spatial visualization in QGIS  

---

## Tools and Technologies

- QGIS 3.40  
- Global Forest Change dataset  
- OTBN shapefile  
- Official cartographic data  

---

## Results

The Moreno department contains:

- 29 census tracts  
- Total population: 32,130 inhabitants  

OTBN categories:

- No Category I (Red) areas recorded  
- Category II (Yellow): 8,004 inhabitants  
- Category III (Green): 372 inhabitants  

Socioeconomic context:

- Average NBI: 28.62%  
- Range: 8.45% – 67.44%  

Deforestation:

- 186,661 hectares in Category II  
- 61,182 hectares in Category III  

### Map Output

<img width="4677" height="3307" alt="mapa3u" src="https://github.com/user-attachments/assets/e5e6b6eb-8036-4aa0-ac06-604a9a497111" />

---

## Conclusions

Although National Law 26,331 represents a significant advance in environmental legislation (Ginzburg & Torrella, 2022), the results highlight the need to strengthen monitoring, control, and enforcement mechanisms.

The findings suggest a relationship between social inequality and intensified natural resource exploitation, leading to the loss of native forests, habitats, and local livelihoods.

Further research should incorporate additional variables such as land tenure structures and foreign capital participation.

---

## Bibliography

- Ginzburg, R., & Torrella, S. (2022). Impacto de la ley nacional de bosques nativos sobre su conservación. Proyección. Estudios Geográficos y de Ordenamiento Territorial, 16(31), 127–158.  
- Hansen, M. C., et al. (2013). High-resolution global maps of 21st-century forest cover change. Science, 342(15), 850–853.  
- Instituto Geográfico Nacional de la República Argentina. (2018). Cartografía de límites. Proyecto SIG 250.  
- Ministerio de Ambiente y Desarrollo Sostenible (MAyDS). (2017, 2019). Ordenamientos territoriales de bosque nativo en el marco de la Ley N° 26.331.
  
---

## Author

Maria Marcela Gomez

