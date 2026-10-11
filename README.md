# Joshua Sojo
I am a student at RCC studying Emergency Management. GIS 8 is a prerequisite course that I enrolled in to better understand maps, their development, and the information they can convey.

## Disease Mapping: Covid-19 Rates and Population Density
This a short video of the interactive swipe map initially showing Covid-19 rates then the population density at the time.

https://github.com/user-attachments/assets/f4501be2-1986-4e2d-b27c-ccda4b11db67

images/Swipe_App_Disease_Mapping.mp4


*Interactive version, live as of September 2026: https://rccgis24.maps.arcgis.com/apps/instant/basic/index.html?appid=1a332f1c67824cf9bf687f68df4c0d34*

**Question:** This small scale map of the five New York boroughs is both a referential and thematic. The referential aspect focuses on clear boundaries of the cities in the five boroughs to help emphasize the thematic properties of Covid-19 rates and population density. 

**Data:** COVID19_ZCTA is a publicly accessible data set layer created and uploaded to ArcGIS Online in November 2024 by GGA_Admin. They reference their Covid-19 case data from the John Hopkins Corona Virus Resource Center and zip code boundaries from Census ZIP Code Tabulation Areas.

**Method:** Following instructions presented by my professor, I was able to add layers to the five boroughs that made choropleth mapping of Covid-19 rates and population density from the data readily available from COVID19_ZCTA. The two layers observed in the video demonstrate the rates and density from high to low with data ranges created from command inputs. Higher value data is represented as dark hues and lower value data is seen as a lighter hue.

**A design choice I made and why:** A design choice I left out while creating a video of these layers changing in real time is not including the data layers tab to identify which layer is being presented before and after. I did this because both layers need to be observable for the swipe transition to show seamlessly and although the named layers could help better identify what is being shown, it still does not directly inform the viewer which is which. The map before the transition is Covid-19 rates and the after is population density.

**A limitation of this map:** This map cannot tell the reader how daily commutes could explain why Covid-19 rates were higher in some lesser dense populated areas. A flow map could resolve this issue.


## 2018 Kilauea Volcanic Eruption: Before and After
In this short video, I display image mapping layers from beginning to end highlighting the before and aftermath of Kilauea's eruption.

https://github.com/user-attachments/assets/a77bc093-efe6-4c0f-b036-6903f3972dd1

*Interactive version, live as of September 2026: https://storymaps.arcgis.com/stories/2aab92b1e35f425c869feba44bdfa654*

**Question:** This a satellite image of Kilauea’s location on the main Hawaiian island, Hawaii. It has very minimal elements with no points of interest, lines, or polygons in place to help distinguish, besides an observable green area that can be considered as vegetation, a coast, and an ocean. What geographical information is given is through satellite images over time showing Kilauea before and after its eruption. 

**Data:** Kilauea 2018 Lava Flow Extents, LS 3 27 2018, LS 7 17 2018, LS 8 2 2018, and LS 2 26 2019 are publicly accessible polygon feature and Landsat images on ArcGIS Online. They were published by Esri_Tutorials in December 2022 (Lava Flow Extents) and spatial-admin_ucsb August 2024 (LS images).

**Method:** Through direction of my professor, these layers were converted into images that could be easily seen and understood compared to their original states. This mainly applied to the Landsat images that were mainly in black and white or had heavy smoke. The bands of the RGB scale were changed so that Hawaii and Kilauea’s eruption could be easily observed.

**A design choice I made and why:** A decision choice I made with the inserted video was taking a couple of second before transitioning between the layer conveying different stages of Kilauea so that the viewer could have a better sense of progression.

**A limitation of this map:** This map is limited in many ways. The viewer does not know if the map is oriented to true north, if it is an island or peninsula, or that there is a volcano within the polygon until images of eruption are shown. Without a description to this map, a lot could be misunderstood about it.

## Data sources
- COVID19_ZCTA, GGA_Admin, 2024, https://rccgis24.maps.arcgis.com/home/item.html?id=c3c352373ab742baa5b753614356001d#overview
- [Dataset name, publisher, year, URL]
- Kilauea 2018 Lava Flow Extents, Esri_Tutorials, 2022, https://rccgis24.maps.arcgis.com/home/item.html?id=2072343705e343c3ad4106214ce88f25#overview
- LS 3 27 2018, spatial-admin_ucsb, 2024, https://rccgis24.maps.arcgis.com/home/item.html?id=7eec0bb14ec9419fac1a54e7cc5d9489#overview
- LS 7 17 2018, spatial-admin_ucsb, 2024, https://rccgis24.maps.arcgis.com/home/item.html?id=e0679720ca0f44a78971a57d44df6db1#overview
- LS 8 2 2018, spatial-admin_ucsb, 2024, https://rccgis24.maps.arcgis.com/home/item.html?id=c250e0833c5541a5842fd31ba8d4ca47#overview
- LS 2 26 2019, spatial-admin_ucsb, 2024, https://rccgis24.maps.arcgis.com/home/item.html?id=2f5a1ade710441e6a450d8004c381390#overview

## Where this is going
I plan to incorporate additional projects created in my geography course that are more interactive. A concept I have learned in my geography class is that maps are a source of information and I’d like to show the projects where the information can be seen from more than just one point of view. My goal is to have more projects that show growth of my interest in creating maps that are interactive and display as much information as possible.
