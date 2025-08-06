# Understanding-Global-Climate-Change
Interactive R shiny app visualizing global climate change related trends

# 🌍 Understanding Global Climate Change – Interactive R Shiny Dashboard

This project is an interactive R Shiny dashboard developed using runtime: shiny in R Markdown. It visualizes key trends and indicators related to global climate change, including temperature rise, greenhouse gas emissions, water stress, energy consumption, deforestation, air pollution, and biodiversity threats.

> 📊 Built with *R, **Shiny, **Plotly, **Leaflet, **ggplot2, and **dplyr*  
> 🧠 Created by Zainab Hanjra

---

## 🚀 Features

- 📈 *Global Temperature Trends* (NASA anomaly data)
- 💧 *Temperature vs Water Stress Correlation*
- 🗺 *Interactive Water Stress Maps* by year
- 🌫 *Air Quality (PM2.5 Pollution)* across countries
- 🔥 *Total Greenhouse Gas Emissions* (Top 10 emitters)
- 🌎 *CO₂ Emissions per Capita Maps* with time filters
- 💵 *GDP vs CO₂ Emissions* animated plot (Top 10 economies)
- ⚡ *Energy Consumption Trends*: fossil, renewable, and nuclear
- 🧱 *Carbon Intensity of GDP* in fossil and alternative-energy users
- 🌲 *Deforestation Heatmaps* by country or region
- 🐦 *Biodiversity Loss*: Threatened bird, mammal, and plant species
- 💀 *Mortality from Air Pollution* by country

---

## 📁 Repository Structure

📦 climate-change-dashboard
┣ 📜 climate_dashboard.Rmd # Main Shiny R Markdown file
┣ 📁 data/ # Contains .rds data files
┣ 📁 images/ # Screenshots or visuals (optional)
┣ 📜 README.md # This file
┗ 📜 summary_table.rds / combined_data.rds


---

## 📦 Dependencies

You need the following R packages:

```r
install.packages(c(
"shiny", "plotly", "leaflet", "ggplot2", "ggrepel",
  "dplyr", "tidyr", "scales", "viridis", "countrycode"
))
```

▶ How to Run Locally
1. Clone the repository:
git clone https://github.com/yourusername/climate-change-dashboard.git
cd climate-change-dashboard


2. Open climate_dashboard.Rmd in RStudio

3. Click "Run Document" (or use the “Knit with parameters” option)

🧪 Make sure the .rds data files (processed_combined_data.rds, summary_table.rds) are in the same directory.

💡 Motivation
This project was developed to:

Visualize the complex interactions between climate variables and human activities

Raise awareness of environmental issues using accessible, interactive tools

Demonstrate proficiency in R-based data science and dashboard development

📚 Acknowledgments
Climate data sourced from NASA, World Bank, and international datasets

Developed as part of a data visualization class project, portfolio and research showcase

👩‍💻 Author
Zainab Hanjra
📘 B.S. Biotechnology | 📊 R Programming
🔗 [LinkedIn](https://www.linkedin.com/in/zainab-hanjra-2a8a09242
📧 zainabhanjra270@gmail.com

📌 License
MIT License (optional) — free to use, share, and adapt with attribution.
  "shiny", "plotly", "leaflet", "ggplot2", "ggrepel",
  "dplyr", "tidyr", "scales", "viridis", "countrycode"
))
