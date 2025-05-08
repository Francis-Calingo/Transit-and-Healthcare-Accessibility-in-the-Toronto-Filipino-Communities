# PROJECT OVERVIEW: Transit and Healthcare Accessibility in the Toronto Filipino Communities
## Table of Contents
* [Overview](#overview)
* [Code and Setup](#code-and-setup)
* [Web Scraping](#web-scraping)
* [Map Development](#map-development)
* [Results](#results)
* [Discussion](#discussion)
* [Assumptions and Caveats](#assumptions-and-caveats)
* [Credits and Acknowledgements](#credits-and-acknowledgements)

---
# Overview

  <ul>
    <li>Used ArcGIS Pro to map relationship between hospital accessibility, transit accessibility, and Toronto's 5 federal ridings (2013 representation order) with highest per-capita Filipino population.</li>
    <li>Scraped 2021 Census Data from Statistics Canada data, hospital locations from Government of Ontario, and transit data from Toronto Star article</li>
    <li>Feature classes digitized: Polygon (Riding boundaries), Line(Busiest bus routes), Point (Hospital locations)</li>
  </ul>

---

# Code and Setup

[Download ArcGIS Pro (version 3.4), must be signed in.](https://pro.arcgis.com/en/pro-app/latest/get-started/install-and-sign-in-to-arcgis-pro.htm)

If you'd like to fork or run this locally:

```bash
git clone https://github.com/Francis-Calingo/Transit-and-Healthcare-Accessibility-in-the-Toronto-Filipino-Communities.git
cd Transit-and-Healthcare-Accessibility-in-the-Toronto-Filipino-Communities
```

[<b>Back to Table of Contents</b>](#table-of-contents)

---
  
# Web Scraping
<ul>
<li><b>CENSUS DATA:</b> https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/index.cfm?Lang=E </li>
<li><b>DATA ON 10 BUSIEST BUS LINES:</b> https://www.thestar.com/interactives/which-ttc-route-had-the-most-delays-in-2023-which-had-the-most-breakdowns-or/article_713836f8-92bd-11ee-8ac7-ffa407d80fe3.html </li>
<li><b>LIST OF HOSPITALS ACCORDING TO THE PROVINCE OF ONTARIO:</b> https://www.ontario.ca/page/general-hospital-locations#section-4 </li>
<li><b>TORONTO FEDERAL RIDINGS WITH HIGHEST PER-CAPITA FILIPINO POPULATION:</b></li>
  <ul>
    <li><b>York Centre:</b>19.3</li>
    <li><b>Scarborough Centre:</b>13.1</li>
    <li><b>Eglinton--Lawrence:</b>10.9</li>
    <li><b>Scarborough--Rouge Park:</b>8.9</li>
    <li><b>Scarborough--Guildwood:</b>8.8</li>
  </ul>
</ul>

[<b>Back to Table of Contents</b>](#table-of-contents)

---

# Map Development

| Feature Class Type  | Description | Feature Class Symbology | Number of Elements | 
| ------------- | ------------- | ------------- | ------------- |
| Polygon | Boundaries of 5 federal ridings in Toronto (2013 representation order) with highest per-capita Filipino population | Light blue outline, varying shades of blue fill, with darker blue representing higher per-capita population | 5 |
| Line | Lines approximating the routes of Toronto's busiest bus routes | Red lines with varying degrees of thickness, thicker lines representing busier routes | 10 |
| Point | Hospital locations | White dots with heart symbol inside | 37 |

[<b>Back to Table of Contents</b>](#table-of-contents)

---

# Results
![Brief Snapshot of Filipino Community in Toronto](https://github.com/user-attachments/assets/3c8202ea-58a0-4506-a346-e3a132873165)

<i> <b>IMAGE DESCRIPTION:</b> Satellite map of Toronto. 5 digitized blue polygons representing the 5 federal ridings in Toronto that have the highest per-capita Filipino population (per 2021 Census). Darker blue shades represent higher percentage, and lighter blue shades represent lower percentage. 10 digitized red lines with labels represent the 10 busiest bus routes from 2023 by ridership. Several digitized points (heart symbol in white circle) represent locations of hospitals in Toronto. Attribute table of the 10 lines is shown, with the list going in ascending order from 10th busiest to most busiest.</i>

Notice that they are concentrated in Toronto's northern suburb (North York) and eastern suburb (Scarborough). Observe that 7 of the 10 busiest routes traverse the highlighted ridings, and two more straddling one or more of their borders. Also observe that the hospitals are more concentrated in the downtown while they become more sparse in the suburbs, especially in Scarborough, despite the fact that well over half a million people live in Scarborough.

[<b>Back to Table of Contents</b>](#table-of-contents)

---

# Discussion

Not only is the Filipino population concenrated in Toronto's northern suburb (North York) as well as its eastern suburb (Scarborough), but the number of general hospitals are sparse in the suburbs while being concentrated in Downtown Toronto. The same is true for Toronto's busiest bus routes, with all but one (32 Eglinton West, which straddles the boundaries on one of the 5 ridings) crossing at least one of the five ridings. However, it is important to note that racialized, immigrant, and lower income communities are also concentrated in Toronto's northern and eastern suburbs. While this is by no means a complete and comprehensive analysis of racial and economic inequalities in terms of transit and healthcare accessibility, it nevertheless is spatial proof that transit and healthcare access is not equal across the city. Therefore, the city should prioritize improving access to both transit and healthcare accessibility, especially in North York and Scarborough. Some action items may include, but are not limited to:

* Performing further spatial analysis to develop new bus routes that mitigates crowding on some of the more busier routes.

* The busier bus routes means that many people from the suburbs heavily rely on public transit to travel. Since we have already mentioned before that racialized, immigrant, and lower income communities are concentrated in the suburbs, the city should strongly consider lowering transit fares to help make it more accessible.

* Institutes should open up more opportunities to train people in the healthcare industry to better serve the suburban communities. [This is an example of such efforts](https://www.utoronto.ca/news/u-t-scarborough-launches-new-academy-medicine-eastern-gta), but more needs to be done.

* Increase accessibility to non-medical facilities that can profoundly improve mental and physical health for suburban residents such as access to more green space and recreational facilities, prioritizing more pedestrian and bicycle-friendly infrastructure over car-centric infrastructure, develop culturally-sensitive health curriculums for schools where the majority of their student populations are immigrants and/or racialized, etc.

[<b>Back to Table of Contents</b>](#table-of-contents)

---

# Assumptions and Caveats

The hospital locations are based on the Government of Ontario's definition of "general hospital", which is why some locations on the map are within each other's vicinities, or even in the same site.

[<b>Back to Table of Contents</b>](#table-of-contents)

---

# Credits and Acknowledgements

“GIS, Mapping, and Spatial Analysis.” University of Toronto. Coursera, https://www.coursera.org/specializations/gis-mapping-spatial-analysis

[<b>Back to Table of Contents</b>](#table-of-contents)


