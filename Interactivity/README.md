# Interactivity

**Contents**
- About
- Dataset
- Script
- Interactivity Features
- Outputs
  1. Interactivity Feature #1 | Hover & Tooltip
  2. Interactivity Feature #2 | Year Slider (*The arrangement of images may lose its structure on smaller screen sizes*)

**About**</br>
This directory contains a script for creating an interactive bar chart for the top 10 countries for CO2 emissions for the selected year on the slider. 

**Datasets**</br>
I used the [CO2 Emission by countries Year wise (1750-2022)](https://www.kaggle.com/datasets/moazzimalibhatti/co2-emission-by-countries-year-wise-17502022) dataset which I found on Kaggle. It is a open source and relatively simple and clean dataset, which can be directly used without any data cleaning.

I have also uploaded the same dataset in this directory and you can find it in the [data/CO2 Emission by countries Year wise (1750-2022)](https://github.com/gauravpatil123/Interactive-Visualizations/blob/main/Interactivity/data/CO2%20Emission%20by%20countries%20Year%20wise%20(1750-2022)/CO2%20emission%20by%20countries.csv) directory.

**Scripts**</br>
- CO2_emmissions.html</br>
Running this script on a server will create a interactive bar chart for the top 10 counties for CO2 emissions for the year 1750. The graph is based on the dataset mentioned above. The script will create a slider on top of the chart to interact with the graph and change the year. The graph will reflect the data for the selected year on the slider.

**Interactivity Features**</br>
  1. The bar chart has a hover feature which changes the color of the bar on which the mouse is currently positioned to highlight the selection. 
  2. Along with hover the chart also has a tooltip feature which shows the CO2 emission value & scale in the tooltip for the selected bar on the chart.
  3. The color scale chosen for the bar chart as well as the hover feature is colorblind safe. - (using Adobe Color).
  4. The slider on top of the chart goes from year 1750 to 2020 with the increment of 1 year.(Full scope of the dataset)
  5. The change in value on the slider will be reflected on the data being shown on the bar chart.

**Outputs**</br>
- Interactivity Feature #1 | Hover & Tooltip</br>
<img src="data/Images/Hover & Tooltip.png" width=400>

- Interactivity Feature #2 | Year Slider</br>
Since there are almost 270 years on the slider which will generate 270 different charts - I have just added images of charts with ceratin intervals.</br>
Notice that the scale of the Y-axis is also changing.</br>
<img src="data/Images/1750.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/1775.png" width=400></br>
<img src="data/Images/1800.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/1825.png" width=400></br>
<img src="data/Images/1850.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/1875.png" width=400></br>
<img src="data/Images/1900.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/1925.png" width=400></br>
<img src="data/Images/1950.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/1975.png" width=400></br>
<img src="data/Images/2000.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/2010.png" width=400></br>
<img src="data/Images/2015.png" width=400> &nbsp;&nbsp;&nbsp; <img src="data/Images/2020.png" width=400></br>
