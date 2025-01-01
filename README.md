# PROJECT OVERVIEW: Transit and Healthcare Accessibility in the Toronto Filipino Communities

  <ul>
    <li>Used ArcGIS Pro to map relationship between hospital accessibility, transit accessibility, and Toronto's 5 federal ridings (2013 representation order) with highest per-capita Filipino population.</li>
    <li>Scraped 2021 Census Data from Statistics Canada data, hospital locations from Government of Ontario, and transit data from Toronto Star article</li>
    <li>Feature classes digitized: Polygon (Riding boundaries), Line(Busiest bus routes), Point (Hospital locations)</li>
  </ul>
  
## Web Scraping
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

## Results and Discussion
![Brief Snapshot of Filipino Community in Toronto](https://github.com/user-attachments/assets/3c8202ea-58a0-4506-a346-e3a132873165)

<i> <b>IMAGE DESCRIPTION:</b> Satellite map of Toronto. 5 digitized blue polygons representing the 5 federal ridings in Toronto that have the highest per-capita Filipino population (per 2021 Census). Darker blue shades represent higher percentage, and lighter blue shades represent lower percentage. 10 digitized red lines with labels represent the 10 busiest bus routes from 2023 by ridership. Several digitized points (heart symbol in white circle) represent locations of hospitals in Toronto. Attribute table of the 10 lines is shown, with the list going in ascending order from 10th busiest to most busiest.</i>

Notice that they are concentrated in Toronto's northern suburb (North York) and eastern suburb (Scarborough). Observe that 7 of the 10 busiest routes traverse the highlighted ridings, and two more straddling one or more of their borders. Also observe that the hospitals are more concentrated in the downtown while they become more sparse in the suburbs, especially in Scarborough, despite the fact that well over half a million people live in Scarborough.
