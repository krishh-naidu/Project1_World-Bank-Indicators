# Project1_World-Bank-Indicators

  This project looks into indicators of world development from the World Bank Developmental Indicators in order to understand how the trajectory of economic growt influences the environment to shed light on profit-driven motives in place of environmental stewardship. The tools used to answer this question included **Jupyter Notebook**, **Python**, **Pandas**, **Gmaps**, **Google API**, **Bokeh**, and **Matplotlib**.

# Navigating this Repository
- The main **Jupyter Notebook** files that were used to generate figures are provided in the *Coding Files* folder
- The folder *Data Files* contains the downloaded and cleaned csv files which were used to generate figures
- *Images* folder contains figure outputs

# Project Work

The questions we posed were:
- What are the general trends for global GDP?
- Is there a correlation between GDP and CO₂ emissions on a global level?
  - Does this mirror the trends of global land and ocean temperatures?
- How do these trends influence urbanization?

  In pursuit of data analysis, the group created line plots of mean GDP growth globally, sum of CO₂ emmissions per year, global land and ocean temperature anomalies, and urban vs. rural populations. Additionally, a scatter plot for comparison of GDP per capita and CO₂ per capita was created in order to elucidate the trend. Also, using gmaps, a color-coded world map was created with 2019 GDP information. 

Though success was found in data visualization, there could be more statistical comparison between the chosen indicators. Future extensions to this project could look into economic indices like income share held by lowest 20% in order to investigate the social effects of capitalism compared to the environmental ones. Also, instead of a global scale, the data could be grouped by region or country in order to compare data more specifically. 

## GDP
![alt text](/Images/GDP_Growth.jpeg)
## GDP vs CO₂
![alt text](/Images/GDPvsCO2Matplotlib.png)
![alt text](/Images/rvalue.png)
![alt text](/Images/GDP_Per_CapitavsCO2Percapita.png)
## Global land and ocean temperature anomalies
![alt text](/Images/GlobalTempoanamolies.png)
![alt text](/Images/GlobalTempBar.png)
## Urbanization
![alt text](/Images/UrbanvsRural.png)
## Gmap
![alt text](/Images/GMAP.jpeg)

Overall, the data suggest a strong correlation (r=.81) between GDP and CO₂ per capita, which also appear to directly correlate with global temperature and urbanization visually.
