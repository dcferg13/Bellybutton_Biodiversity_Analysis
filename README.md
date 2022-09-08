# Bellybutton_Biodiversity
To build a website dashboard about the diversity of the human belly button. The dashboard includes three charts and a panel that has information based on the 
participate. 
## Overview
  The purpose of this repository is to create a dashboard for the participants of the belly button study. The dashboard includes a panel that holds the demographic information of each participant. This panel was created but using d3.json() to grab the participants information from a json file. The dashboard also includes 3 charts. The bar chart shows the top ten bacteria in each participants belly button; the gauge chart shows the amount of time a participant washes their belly button and lastly a bubble chart that shows the overall number of bacteria found in belly buttons. 
## Results
The bar chart also used d3.json() to collect the data from the json file with all the complete data from the study. However, the bar chart only shows the top ten bacteria found in a particular belly button from the selected participant in the panel. 
The gauge chart shows the belly button washing frequency, how scrubs per week, based on the selected participate in the panel. The gauge uses a range by two (0-2, 2-4, etc.) to indicate the number of scrubs per week. We go the washing frequency from the metadata array from the data json file. 
Lastly, the bubble chart shows the overall number of bacteria found all the belly buttons from the study. With the size of the bubbles corresponding to the number of values of bacteria. 

![bio_diversity_web_page](https://user-images.githubusercontent.com/107289345/189223954-a21c2956-bca3-451d-a12b-17f037b95a9a.png)

## Summary
In summary, in this webpage a participate can select their id number from the drop box and the demographic information panel, bar chart and gauge chart will correspond to the information generated from the study. A recommendation for the future would be to have table that explores the different types of bacteria found in the belly button, and where else the bacteria could be found. 
