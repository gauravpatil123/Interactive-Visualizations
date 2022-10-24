# Drawing Data Pt 2: Color & Accessibility

**Contents**
- About
- Dataset
- Script
- Interactivity Features
- Outputs
  1. Drawing 1 | World Disaster Risk Dataset Infograph
  2. Drawing 2 | Infograph Legend
  
**About**</br>
This directory contains a script for creating an interactive bar chart for the top 10 countries for CO2 emissions for the selected year on the slider. 

**Datasets**</br>
I used the [CO2 Emission by countries Year wise (1750-2022)](https://www.kaggle.com/datasets/moazzimalibhatti/co2-emission-by-countries-year-wise-17502022) dataset which I found on Kaggle. It is a open source and relatively simple and clean dataset, which can be directly used without any data cleaning.

I have also uploaded the same dataset in this directory and you can find it in the [data/CO2 Emission by countries Year wise (1750-2022)]() directory.

**Scripts**</br>
- CO2_emmissions.html</br>
Running this script on a server will create a interactive bar chart for the top 10 counties for CO2 emissions for the year 1750. The graph is based on the dataset mentioned above. The script will create a slider on top of the chart to interact with the graph and change the year. The graph will reflect the data for the selected year on the slider.

**Interactivity Features**</br>
  1. The bar chart has a hover feature which cheanges the color of the bar on which the mouse is currently positioned to highlight the selection. 
  2. Along with hover the chart also has a tooltip feature which shows the CO2 emmission value & scale in the tooltip for the selected bar on the chart.
  3. The color scale chosen for the bar chart as well as the hover feature is colorblind safe. - (using Adobe Color).
  4. The slider on top of the chart goes from year 1750 to 2020 with the increment of 1 year.(Full scope of the dataset)
  5. The change in value on the slider will be reflected on the data being shown on the bar chart.

**Outputs**</br>
- Interactivity Feature #1 | Hover & Tooltip
<img src="data/Images/Hover & Tooltip.png" width=500>

- Drawing 2 | Infograph Legend
<img src="data/Images/1750.png" width=675 height=500>
