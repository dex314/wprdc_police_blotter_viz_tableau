# wprdc_police_blotter_viz_tableau
A Tableau visualization based on WPRDC Pittsburgh Police Blotter data sets with some aggregations performed in a Python notebook.
Hopefully this is a working notebook where I can find time to make more updates and expand.

The Tableau link:
https://public.tableau.com/shared/SKJFDDSDJ?:display_count=yes&:origin=viz_share_link

The shared workbook is broken up into three sections:
- Geographic Map of incidents.
- Tree Map of Neighboorhoods and incidents and counts.
- Pie chart of breakdown of time of day of incidents.

The Tree and Pie portions are filterable to the geographic map. Clicking on a neighborhood will focus in on that geography of incidents and clicking on a time pie slice will focus in on that time block.

The jupyter notebook connects to WPRDC data by URL and is located in this repo.

You can find the original data here:

https://data.wprdc.org/dataset/uniform-crime-reporting-data
