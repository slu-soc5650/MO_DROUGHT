# `MO_DROUGHT`

### Repository Contents
This repository contains files for:
-   `MO_DM_20161227/` - Drought data for 27 Dec 2016
-   `MO_DM_20170103/` - Drought data for 3 Jan 2017
-   `MO_DM_20170110/` - Drought data for 10 Jan 2017
-   `MO_DM_20170117/` - Drought data for 17 Jan 2017
-   `MO_DM_20170124/` - Drought data for 24 Jan 2017
-   `MO_DM_20170131/` - Drought data for 31 Jan 2017
-   `MO_DM_20170207/` - Drought data for 7 Feb 2017
-   `MO_DM_20170214/` - Drought data for 14 Feb 2017
-   `LICENSE.md`
-   `README.md`
-   `.gitignore`

### About the Missouri Drought Data
These data were obtained from [The National Drought Mitigation Center](http://droughtmonitor.unl.edu), which is located at the University of Nebraska. They operate in partnership with the United States Department of Agriculture and the National Oceanic and Atmospheric Administration. Each week, they released a drought monitor report that includes maps, tabular data, and [spatial data](http://droughtmonitor.unl.edu/MapsAndData/GISData.aspx). Their spatial data includes shapefiles that detail the extent of drought conditions throughout the United States. These were clipped to Missouri's boundaries for eight reporting periods covering the very end of December, 2016 through mid-February, 2017. The key field is `DM`, which can take on the following values:
*   `0` = `Abnormally Dry`
*   `1` = `Moderate Drought`
*   `2` = `Severe Drought`
*   `3` = `Extreme Drought`
*   `4` = `Exceptional Drought`

These data focus on general trends, so local conditions may vary. One important piece of information not included in the data themselves are the duration of drought conditions. As of February 14, 2017, the drought conditions in Missouri were considered short term (i.e. having a duration of less than six months to date).

#### Narrative Summaries
There is also [textual data](http://droughtmonitor.unl.edu/MapsAndData/NarrativeArchive.aspx) that accompanies the drought reports. The following are the narratives for the reporting periods covered by the data.

##### 27 Dec 2016
"Most of the Midwest received some precipitation, resulting in minor trimming of existing dryness (D0). Heavier rain was confined to areas near the Ohio River and points south. Meanwhile in the upper Midwest, a growing number of weather stations have broken annual precipitation records. Through December 27, for example, year-to-date precipitation reached 40.32 inches in Minneapolis-St. Paul, Minnesota, and 44.76 inches in La Crosse, Wisconsin. Previous (and long-standing) records had been 40.15 inches in 1911 and 44.74 inches in 1881, respectively."

##### 3 Jan 2017
"Precipitation was minimal across much of the region, with the largest totals found in the eastern and southern Ohio Valley (0.5-1.2 inches), upper Midwest and western Great Lakes region (0.3-1 inch), and from northwestern Missouri northeastward into the UP of Michigan (0.3-0.8 inches). In northeastern Indiana and northwestern Ohio, some of the D0 was trimmed away where precipitation exceeded an inch. Temperatures averaged above normal, with most locations reporting weekly anomalies of 5 to10 deg F. Most of the northern portion of the Midwest was snow covered and drought free. In contrast, dry weather during the past 60- and 90-days has led to shortages of 3-6 and 4-8 inches, respectively, in parts of Missouri and western Illinois, thus D1 was expanded in southwestern and southeastern Missouri, and developed in central and northeastern Missouri and western sections of Illinois. The rest of the Midwest stayed unchanged."

##### 10 Jan 2017
"Little or no precipitation fell during the week in most areas as well below normal temperatures dominated the weather in the Midwest. Fortunately much of the region has adequate moisture and surpluses, with abnormal dryness and drought limited to a few small D0 areas in the Ohio Valley and D0-D1 in Missouri and southern Iowa. In western Ohio and eastern Indiana, however, enough precipitation (0.5-1 inch) fell on the D0 area that short-term deficiencies were negated in most locations. Farther west, 0.2-0.4 inches of precipitation maintained the D0 in central and southern parts of Indiana and Illinois. In Missouri, however, little or no precipitation this week and subnormal precipitation during the past 3-months (extending southwestward into the south-central Great Plains) has accumulated deficits of 4-8 inches, with SPIs at D2-D4 levels out to 4-months. USGS stream flows have also dropped into the lower 25th percentile across most of the state. As a result, D1 was greatly expanded in Missouri to cover the largest deficits and most negative SPIs."

##### 17 Jan 2017
"Substantial precipitation brought improvement to many of the dry areas from Iowa and northern Missouri eastward through Ohio, and enough fell elsewhere to prevent any deterioration. Generally 1.5 to locally over 3.0 inches dampened much of northern and southern Illinois, most of Indiana, and northern Ohio, prompting removal of D0 from Ohio and Indiana, with smaller areas of improvement noted farther west. Central Illinois, northern Missouri, and most of southeastern Iowa remained in D0 to D1. Less than half of normal precipitation fell during the last 30 days across much of northern Missouri and parts of central and southern Illinois."

##### 24 Jan 2017
"Light to locally moderate precipitation was measured across the northern half of Arkansas and most of Missouri. Generally 0.5 to 1.5 inches fell on many sites from central Missouri southward, with totals approaching 2 inches in a few patches. For the last 30 days as a whole, the 1.5 to 3.5 inches measured in most areas allowed moisture deficits to increase slightly, and deterioration – rare of late nationally – was noted in parts of north-central Arkansas (to D2) and 2 small patches near central Missouri (to D1). Precipitation totals for the last 3 months are at least 4 inches below normal over most of the D1 and D2 areas, with shortfalls topping 6 inches in spots. Farther east, the region’s only improvement was noted in east-central and southeastern Illinois, where D0 retracted westward, and along the far southeastern tier of the dry region, which was on the fringes of the heavy precipitation in the Southeast."

##### 31 Jan 2017
"The Midwest saw improvements on the map in west-central and southwestern Illinois in areas of Abnormally Dry (D0) and Moderate Drought (D1) as well as in Missouri in areas of Moderate Drought (D1). Despite precipitation deficits during the past 90 days across parts of Illinois and Missouri, drought-related impacts are not being observed at this time in relation to time of year. In the areas of improvement, streamflows are normal and satellite-based soil moisture measurements associated with the NASA Soil Moisture Active Passive mission (SMAP - [https://smap.jpl.nasa.gov](https://smap.jpl.nasa.gov)) show improvements to soil moisture during the past month. Additionally, field-based observations in Missouri show local ponds being full to nearly full. Average temperatures for the week were above normal with the greatest anomalies observed in northern portions of Minnesota and Wisconsin as well as Upper Peninsula Michigan. According to the NWS NOHRSC, 90% of the Northern Great Lakes region is covered by snow."

##### 7 Feb 2017
"On this week’s map, no changes were made. Average temperatures for the week were above normal with the greatest anomalies observed in Iowa, central Missouri, and southern Minnesota where temperatures were 4 to 8 degrees above normal while extreme northern Minnesota, Wisconsin, and Upper Peninsula Michigan were below normal. During the past week, the region was generally dry with some light precipitation accumulations observed in northern portions of Minnesota and Wisconsin, Ohio, and the Upper Peninsula Michigan."

##### 14 Feb 2017
"On this week’s map, a long swath across central and eastern Missouri was degraded from abnormally dry (D0) conditions to moderate drought (D1). Streamflows in the area have plummeted over the past two weeks to less than 25 percent of normal."

### About SOC 4650/5650: Introduction to Geographic Information Science
This class introduces both the theoretical and technical skills that constitute the nascent field of Geographic Information Science (GISc). Techniques introduced include data cleaning and management, map production and cartography, and the manipulation of both tabular and spatial data. The impacts of GISc on public policy, and the effects of public policy on GISc, are also discussed. The course incorporates a wide variety of social, economic, health, urban, meteorological, and environmental data. These data are mapped at a variety of extents, from the City of St. Louis to the St. Louis Metropolitan region, Missouri, all United States counties, and all U.S. states.

### About Christopher Prener, PhD
[Christopher Prener](http://chrisprener.net) (Ph.D., Northeastern University, 2015) is an urban and medical sociologist with an interest in mixed methods research designs that incorporate spatial data. His dissertation examined the effect of neighborhood context and conditions on emergency medical services work, particularly with patients who have mental illnesses or substance use disorders. He is also part of a research team examining the effect of literacy on mental health service use and recovery. He is an Assistant Professor in the Department of Sociology and Anthropology at Saint Louis University. More details are available at [his website](http://www.chrisprener.net) and he can be contacted at [prenercg@slu.edu](mailto:prenercg@slu.edu).

### About Saint Louis University
[Saint Louis University](http://wwww.slu.edu) is a Catholic, Jesuit institution that values academic excellence, life-changing research, compassionate health care, and a strong commitment to faith and service. Founded in 1818, the University fosters the intellectual and character development of more than 13,000 students on two campuses in St. Louis and Madrid, Spain. Building on a legacy of nearly 200 years, Saint Louis University continues to move forward with an unwavering commitment to a higher purpose, a greater good.
