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

These values are defined on [The National Drought Mitigation Center's website](http://droughtmonitor.unl.edu/aboutus/classificationscheme.aspx).

These data focus on general trends, so local conditions may vary. One important piece of information not included in the data themselves are the duration of drought conditions. As of February 14, 2017, the drought conditions in Missouri were considered short term (i.e. having a duration of less than six months to date).

#### Narrative Summaries
There is also [textual data](http://droughtmonitor.unl.edu/MapsAndData/NarrativeArchive.aspx) that accompanies the drought reports. The following are the narratives for the reporting periods covered by the data.

##### 4 Oct 2016
"Dry and warm conditions dominated the Midwest this week, which is not much of a complaint for agricultural producers who are in harvest mode. Some areas from eastern Illinois into Michigan, Indiana, and Ohio did record up to 2 inches of rain, but most of the rest of the region was dry. Temperatures were generally normal in the southern portions of the Midwest to 6-8 degrees above normal in the north. The recent rains did allow for improvements to materialize this week, with a full category improvement for most of Michigan and Ohio, eliminating the moderate drought and leaving behind some lingering D0. Abnormally dry conditions were also improved over southern Indiana and northern Kentucky. As we go into the fall harvest and recharge period, most areas of the Midwest do not have any drought concerns."

##### 11 Oct 2016
"Most of the Midwest was dry this week, allowing for harvest activities to take off in full force. Some areas of western Iowa and northern Missouri did record up to 3 inches of rain for the week and most areas were 4-6 degrees above normal. Abnormally dry conditions were introduced into much of southern Kentucky this week and into the boot-heel of Missouri too. Moderate drought was introduced in eastern Kentucky while pockets of dryness are scattered in the region. No other changes were made this week."

##### 18 Oct 2016
"Increasingly dry conditions were noted, particularly in southern and eastern portions of the region. Abnormal Dryness (D0) and Moderate Drought (D1) expanded northward over much of Kentucky into southern Indiana and southwestern Ohio. 60-day rainfall in many of these areas has totaled less than 50 percent of normal, with the D1 generally corresponding with the lowest streamflows and soil moisture."

##### 25 Oct 2016
"The Midwest saw some minor improvements on the map concentrated in eastern Ohio where locally heavy rainfall accumulations (two-to-three inches) led to removal of areas of Abnormally Dry (D0). In Kentucky, short-term precipitation deficits during the past 60 days led to expansion of Moderate Drought (D1) in the south-central region. In Michigan, recent rainfall and improving hydrologic conditions led to removal of two areas of Abnormally Dry (D0). Across the rest of the region, the map remained status quo for the week. Average temperatures were slightly below normal in northern Minnesota while the rest of the region was two-to-eight degree above normal with the greatest anomalies in Kentucky and Ohio."

##### 1 Nov 2016
"Much of the Midwest remained drought-free. In the Lower Ohio Valley, continued rainfall shortages combined with temperature departures of up to 12 degrees above normal resulted in a full category intensification of drought conditions in central and western Kentucky. The majority of the state is now in moderate (D1) drought. In eastern Tennessee, exceptional (D4) and extreme (D3) drought expanded to the northeast with moderate (d1) drought now covering the remainder of the state."

##### 8 Nov 2016
"Much of the Midwest continued to remain drought-free, though southern Ohio saw an expansion of D0. Continued rainfall shortages combined with above-normal temperatures have caused continued dryness across Kentucky and Tennessee. Severe drought (D2) was introduced into south-central Kentucky and moderate drought (D1) was expanded to the western part of the state due to precipitation deficits, wildfire activity, and low soil moisture. In Tennessee, severe drought (D2) was expanded in the central part of the state and exceptional drought (D4) crept eastward."

##### 15 Nov 2016
"One to 2 inches of rain fell in parts of Texas, and North Dakota had a tenth of an inch or less, but most of the Great Plains had no precipitation this week. There was some contraction of D0 in Texas where the rains fell, but more expansion of D0-D2 occurred with the addition of a new oval of D3 over northeast Texas and adjacent southeast Oklahoma. D0-D2 also expanded in parts of Oklahoma, D0 expanded in Iowa and Missouri and adjacent parts of Illinois, and D0-D1 expanded in western Kansas and Nebraska and adjacent parts of Colorado. The Oklahoma State Climatologist's office has received widespread reports of low or dry farm ponds, dry soils and ruined crops. In LeFlore County, cattle producers are already feeding hay due to the lack of forage caused by drought conditions, and water supplies in the northern half of the county are becoming very depleted. Reports of drought impacts in the Arklatex, received by National Weather Service personnel, include much lower than usual stock ponds and significant risk for wildfires."

##### 22 Nov 2016
"Western portions of the Ohio Valley received half an inch to an inch of rain, but amounts dropped off to only a couple tenths to the east. Parts of eastern Indiana were the only areas with weekly precipitation near normal. D2-D3 expanded across Kentucky with D1-D2 straddling the Ohio River. D0 spread further into Ohio, Indiana, and Illinois. Agricultural impacts received by the Kentucky State Climatologist include dry farm ponds, producers feeding hay early, and winter wheat struggling.

The cold front fell apart as it moved across the Southeast, leaving the region with another week of zero precipitation. As reported by the National Interagency Fire Center (NIFC), hundreds (at least 212) new fires have started in the Southeast, with 30 of them classified as large wildfires (100 acres or more), and burn bans were widespread across the region. Streams were at record and near-record low levels. Severe agricultural impacts (stock ponds drying up, winter feed being used to keep cattle alive since fall started) were widespread across the South and Southeast. Significant expansion of D0-D4 occurred across the southeastern States. In the Lower Mississippi Valley, D1-D3 expanded across Mississippi, Louisiana, and Arkansas, and D0-D2 expanded in Missouri. In Alabama, ponds were drying up in and around Lowndes County, and cattlemen were hauling water and using winter hay to feed cattle since late summer. As of November 22, Oneonta, Alabama, in the northeast part of the state, has gone 94 consecutive days without measurable precipitation. In Mississippi, the USDA has received reports of ponds drying up and cattle producers having to feed hay, in some cases already using up their entire hay supply for the winter months. Rye grass that was planted in the beginning of October has yet to emerge. As described by the Georgia State Climatologist, agricultural impacts due to dry soils in Turner/Tift/Irwin/Worth/Ben Hill/Wicox/Dodge county areas have been just detrimental for peanut and cattle farmers. In Decatur County, dryland winter forage is not being attempted at this time. If there is no irrigation, the small grains have emerged and died. In Coffee County, unless irrigated, small grains for grazing are naught. In Coweta County, hay is becoming harder to find and even irrigated areas are now suffering due to low water levels in ponds and creeks. The USDA has received reports of wells going bad and stock ponds drying up in Holmes County, Florida. According to November 20 USDA reports, 100% of the topsoil moisture and 98% of the subsoil moisture in Alabama was rated short or very short (dry or very dry)."

##### 29 Nov 2016
"Two to 4 inches of rain fell in a band from northeast Texas to southern Indiana, and across parts of central Alabama to central Georgia, as the cold fronts passed through the region. Over 4 inches was reported at a few stations in northeast Texas, northwest Louisiana, and southeast Missouri. Amounts ranged from half an inch to an inch and a half further east, but little to no rain fell by the USDM cutoff date across southeast Alabama and much of Florida to North Carolina. With November precipitation deficits through November 27, before the heavier rains fell, ranging from 3 to 5 inches across the driest parts of the Southeast, and year-to-date deficits ranging from 12 to 20 inches, locally well over 20 inches, 2 to 4 inches of new rain this week did little to alleviate the long-term dryness.

D1-D3 were pulled back in parts of the Lower Mississippi Valley to Ohio Valley, from Arkansas and Louisiana to Indiana and Ohio. D0 was largely left in place because the weekly rainfall amounts were not enough to eliminate even the month-to-date deficits in the D0 areas, except in parts of northwest and southwest Indiana where D0 was trimmed. D3-D4 were pulled back slightly in parts of east central Mississippi to west central Georgia, mainly where 2.5+ inch rains fell."

##### 06 Dec 2016
"Precipitation amounts ranged from 2-8 inches across most of Tennessee during the past 7-days, and about 2-4 inches in southeast Kentucky. A one-category improvement was made in these areas. During the past 14-days, 3-6 inches of rain was observed in a region centered near Memphis, TN, which included the Missouri bootheel, far western Kentucky, eastern Arkansas, southwest Tennessee and adjacent parts of Mississippi. A one-category improvement was also made for these areas. USGS stream flow gauges generally indicate near-average stream and river flows."

##### 13 Dec 2016
**no specific narrative**

##### 20 Dec 2016
"The Ohio Valley received heavy precipitation, with Louisville, Kentucky (2.22 inches), and Cincinnati, Ohio (1.76 inches), reporting daily-record totals for December 17. Accordingly, coverage of dryness (D0) and moderate to severe drought (D1 to D2) was reduced or eliminated where heavy rain fell. Farther west, however, coverage of abnormal dryness expanded in the middle Mississippi Valley and environs, while some additional moderate drought (D1) crept into southern Missouri. December 1-20 precipitation totaled less than one-third of an inch (12 to 16% of normal) in Missouri locations such as Springfield, Joplin, and West Plains. Several weeks ago, on November 27—prior to the December dryness—topsoil moisture was rated 50% very short to short in southwestern Missouri."

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
