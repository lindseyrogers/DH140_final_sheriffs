# Examining Police and Sheriff Violence through Data

## Link to myBinder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lindseyrogers/DH140_final_sheriffs.git/HEAD)

## Contents of this repo
1. final_sheriffs notebook
2. Simplified Mapping Police Violence Datasets and boundary geoJSON files
3. Requirements file
4. README file


## Project Background
Constitutional Sheriffs are a self-described group of elected county sheriffs that subscribe to the belief that the local sheriff is the highest authority in the United States. They believe their power is higher than both the federal and state government, leaving them the power to decide which laws are unconstitutional and are not to be enforced. Most notably, these sheriffs have refused to enforce COVID and gun control regulations.

Studying Constitutional Sheriffs is difficult because there is not a complete and definite list of Constitutional Sheriffs as members are self-described. To study these sheriffs, I am working on developing a working list of Constitutional Sheriffs and addressing sheriff trends with proxy data. For this class, I will be using Python coding skills to address the following research questions:

### How has sheriff and police violence changed over time?
### Where is sheriff violence happening? Are there spatial trends that emerge from the data?

This project uses two primary datasets for analysis. The first dataset is the Mapping Police Violence database. This is a collection of data on civilians killed by police or sheriff officers since 2013. The dataset has over 10,000 entries with information such as the name of the victim, the agency responsible, and the lat and long location of the death. This dataset was downloaded from the link, then I simplified the dataset in excel and uploaded the simplified dataset to my personal github. The second dataset is the UCLA Law COVID 19 Behind Bars dataset. This dataset is primarly focued on collecting information relating to deaths within US federal prisons. Relating to sheriff violence, there are a few points of data relating to deaths within county prisons. This data, collected by facility, will be extracted for analysis. This dataset is accessed through the UCLA Law Behind Bars github.

## Data Used
|Data Source|
|:---:|
|[Mapping Police Violence](https://mappingpoliceviolence.org/)|
|[UCLA Law Behind Bars](https://uclacovidbehindbars.org/)|
|[Geoboundaries](https://github.com/wmgeolab/geoBoundaries)|
|[Folium US Boundaries](https://raw.githubusercontent.com/python-visualization/folium/master/examples/data/us-states.json)



