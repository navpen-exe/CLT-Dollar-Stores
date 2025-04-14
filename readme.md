# Dollar Stores and Income in Mecklenburg County (Charlotte, NC)
An webmap showing how dollar store locations correlate with low-income areas

## 📌 Project Overview
- Visualize the distribution of dollar stores in Mecklenburg County 
- Visualize how that distribution mirrors the distribution of income

## 🛠️ Tools
- Leaflet.js - Web mapping JavaScript library
- Chroma.js - Color library for showing income data
- QGIS - Analyzing editing GeoJSON files

## 📋 Data Sources
- Dollar Store Locations - [OpenStreetMap](https://overpass-turbo.eu)
Income Data - [Census Bureau](https://data.census.gov)
Basemap - [Stadia Maps](https://stadiamaps.com) and [Stamen Design](https://stamen.com)

## 💲 Icons
- Dollar Tree, Public domain, via Wikimedia Commons
- Dollar General - World Vector Logo, Public domain, via Wikimedia Commons
- Family Dollar - Tellermate 2021, CC BY-SA 4.0, via Wikimedia Commons

## 🎨 Design Considerations
- **Why is darker red lower income? Shouldn't darker colors represent more of a phenomenon?**
    - I felt that darker red to represent lower income was more appropriate, as it feels reminiscent of historical redlining maps, with redlining, and similar historical discrimination, being one of the major factors in creating the spatial patterns of income we see today.

## 📂 File Structure
<code>
project-folder/ <br/>
├── index.html &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;# Main web page <br/>
├── data/ <br/>
│   ├── Income-CLT.geojson &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;# Census tract income data <br/>
│   └── Dollar-Store-Locations.geojson &nbsp;# Store locations <br/>
├── icons/ <br/>
│   ├── DG.png &nbsp; &nbsp; # Dollar General logo <br/>
│   ├── FD.png &nbsp; &nbsp; # Family Dollar logo <br/>
│   └── DT.png  &nbsp; &nbsp; # Dollar Tree logo <br/>
└── README.md  &nbsp;&nbsp; # This file
</code>
