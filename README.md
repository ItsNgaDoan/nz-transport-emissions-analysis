# New Zealand Transport Emissions Analysis  
Evaluating Energy Use, Emissions Efficiency, and Innovation Pathways  

This project analyzes New Zealand’s transport sector to assess its **emissions intensity, energy consumption, and economic efficiency**, and benchmark its performance against other OECD countries.

The goal is to understand whether New Zealand is progressing toward its **emission reduction targets**, and what strategies can be learned from leading countries.


## Overview  

Transport is one of the **largest contributors to greenhouse gas emissions in New Zealand**, making it a critical sector for achieving national climate goals, including:

- 50% emissions reduction by 2030 (NDC target)  
- 41% reduction in transport emissions by 2035  
- Net zero emissions by 2050 (Paris Agreement)  

This project evaluates New Zealand’s performance using OECD data and identifies opportunities for improvement.

The analysis focuses on three key dimensions:

- **GHG Intensity** – emissions relative to economic output  
- **Energy Consumption** – energy use in the transport sector  
- **Transport Efficiency** – economic output generated per unit of emissions  


## Data and Methodology  

The analysis is built on a core OECD dataset and enriched with additional indicators to provide a multi-dimensional view of transport emissions.

### Data sources
- OECD Data Explorer (GHG emissions, GDP, energy consumption)  

### Approach
1. Collected and combined multiple datasets across OECD countries  
2. Performed data cleaning and transformation (handling missing values, aligning formats)  
3. Calculated key metrics:
   - GHG Intensity = Emissions / GDP  
   - Transport Efficiency = GDP / Transport Emissions  
4. Conducted **correlation analysis** to examine relationships between energy use and emissions  
5. Applied **web scraping (Python)** to collect global patent data on emission reduction technologies  
6. Benchmarked New Zealand against leading countries  


## Key Findings  

### 1. New Zealand shows slower progress in emissions intensity  
- GHG intensity decreased by approximately **28%**, indicating progress  
- However, New Zealand still lags behind top-performing OECD countries  


### 2. Strong link between energy use and emissions  
- Correlation between transport emissions and energy consumption:  
  - **New Zealand: 0.68**  
  - **OECD average: 0.57**  

This suggests New Zealand’s emissions are **more sensitive to energy consumption**, indicating lower efficiency.


### 3. Lower efficiency in economic output per emission  
- New Zealand generates **less GDP per unit of transport emissions** compared to leading countries  
- This highlights inefficiencies in converting energy use into economic value  


### 4. Innovation plays a key role in emissions reduction  
To understand how leading countries reduce emissions, a **Python-based web scraping approach** was used to collect patent data related to:

- emission reduction technologies  
- renewable energy in transport  
- sustainable fuel systems  

Leading countries invest in:
- electric vehicle incentives (Denmark)  
- advanced biofuels and hydrogen (Japan)  
- rail-based logistics systems (Germany, Spain)  


## Strategic Implications  

### Improve energy efficiency in transport  
New Zealand’s high correlation between energy use and emissions suggests a need to **improve efficiency**, not just reduce consumption.


### Accelerate adoption of clean technologies  
Policies such as:
- EV incentives  
- renewable fuels  
- hydrogen technologies  

can significantly improve emissions performance.


### Invest in alternative transport systems  
Rail-based logistics and public transport systems offer **long-term emission reductions** while maintaining economic productivity.


### Use benchmarking for decision-making  
Cross-country comparison provides a **data-driven framework** to evaluate and improve national strategies.


## Technical Implementation  

- Built using **Python (Jupyter Notebook)** for data analysis and web scraping  
- Performed correlation analysis and metric calculations  
- Developed a **web scraper** to extract patent data from Google Patents  
- Integrated datasets into a unified analytical workflow  


## Analysis Preview  

![GHG Intensity](./screenshots/q1-ghg-intensity.png)

![Transport Emissions vs Energy](./screenshots/q2-transport-emissions-vs-energy.png)

![Transport Efficiency](./screenshots/q3-efficiency.png)

![Patent Analysis](./screenshots/q4-patents.png)

![Implications](./screenshots/implications.png)


## Important Note  

The visualisations in this repository are static representations of the analysis.

For full reproducibility and detailed exploration, please refer to the Jupyter Notebook:

👉 `transport-emissions-analysis.ipynb`


## My role and contribution  

This project was completed as part of a group assignment.

My contributions focused on the data preparation and analytical workflow:

- identified and integrated relevant datasets to support the analysis and shape the project narrative  
- performed data cleaning, wrangling, and transformation across multiple sources  
- combined datasets into a structured format ready for analysis  
- developed the Python notebook to conduct analysis and present results  
- contributed to translating analytical outputs into clear, structured insights  


## Tools and Technologies  

- Python (pandas, numpy, matplotlib, seaborn)  
- Web scraping (Selenium / requests / BeautifulSoup)  
- Jupyter Notebook  
- OECD Data Explorer  
