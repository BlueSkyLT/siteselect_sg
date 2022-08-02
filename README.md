# The Land &amp; Transport Singapore (LTSG) dataset

### Dataset Description:
The LTSG dataset contains Points of Interest (POIs), HDB buildings and public transportation data of Singapore. The dataset aims to provide an overview of the urban life of the city state. The POI data contains data points of places that people have an interest in visiting for a certain purpose, which include but not limited to educational institutes such as schools or libraries, shopping places such as supermarkets or convenience stores, recreational places such as parks or bars. Generally speaking, the POI data can tell us what kind of activities are happening at the location. The HDB data contains data points of apartment buildings where people reside. In short, the HDB data shows where people are staying, while the POI data shows where people are visiting. Every day, people travel between these locations, forming a certain connection between them. With the bus routing data, the bus ridership data and the subway routing data, we hope to provide information on the system that supports these travels. Thus, this dataset has the potential to be used by researchers in the field for many different tasks that require knowledge of transport, recreational, commercial and residential information of a city, especially to explore their influence on each other.
The data are gathered from various sources including [DataMall](https://datamall.lta.gov.sg/content/datamall/en.html), [Data.gov.sg](https://data.gov.sg), [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview), [OneMap API](https://www.onemap.gov.sg/docs/).

Within the dataset:
- ```poi.csv``` contains 8672 POIs around Singapore. Attributes include their Google user ratings and number of ratings, the POI types (list of types can be found [here](https://developers.google.com/maps/documentation/places/web-service/supported_types)), and their street address, etc.
- ```hdb.csv``` contains 12442 HDB buildings in Singapore. Attributes include their block number, street address, zipcode, the year when they were built, the number of dwelling units, and the functionality of the building, etc. 
- ```bus_line.csv``` contains 5049 bus stations and their routing information.
- ```bus_vol.csv``` contains 5018 bus stations and their passenger volume information during July, August, and September 2021.
- ```mrt.csv``` contains 166 subway stations and their routing information.

All of the data comes with location (in longitude and latitude) and administrative division (by subzone, planning area, and region) information.

### Project Site
The project site is [here](https://sites.google.com/view/ltsg).

### Download
You can download the complete dataset from [here](https://entuedu-my.sharepoint.com/:u:/g/personal/lant0003_e_ntu_edu_sg/EVUr_QwsB1pPvP6r3MMYQS4BXWvjvVAg1PzINtpgoTvlMg?e=T3B2n1).

### Paper
Paper available [here](https://doi.org/10.3390/rs14153579).

Bibtex:
```
@Article{rs14153579,
AUTHOR = {Lan, Tian and Cheng, Hao and Wang, Yi and Wen, Bihan},
TITLE = {Site Selection via Learning Graph Convolutional Neural Networks: A Case Study of Singapore},
JOURNAL = {Remote Sensing},
VOLUME = {14},
YEAR = {2022},
NUMBER = {15},
ARTICLE-NUMBER = {3579},
URL = {https://www.mdpi.com/2072-4292/14/15/3579},
ISSN = {2072-4292},
ABSTRACT = {Selection of store sites is a common but challenging task in business practices. Picking the most desirable location for a future store is crucial for attracting customers and becoming profitable. The classic multi-criteria decision-making framework for store site selection oversimplifies the local characteristics that are both high dimensional and unstructured. Recent advances in deep learning enable more powerful data-driven approaches for site selection, many of which, however, overlook the interaction between different locations on the map. To better incorporate the spatial interaction patterns in understanding neighborhood characteristics and their impact on store placement, we propose to learn a graph convolutional network (GCN) for highly effective site selection tasks. Furthermore, we present a novel dataset that encompasses land use information as well as public transport networks in Singapore as a case study to benchmark site selection algorithms. It allows us to construct a geospatial GCN based on the public transport system to predict the attractiveness of different store sites within neighborhoods. We show that the proposed GCN model outperforms the competing methods that are learning from local geographical characteristics only. The proposed case study corroborates the geospatial interactions and offers new insights for solving various geographic and transport problems using graph neural networks.},
DOI = {10.3390/rs14153579}
}
```

Use
---
All data is subject to copyright and may only be used for non-commercial research. In case of use, please cite our publication.

Contact Tian Lan (lant0003@ntu.edu.sg) for any questions.

Update and Fix
-----
Update Aug 2, 2022.
