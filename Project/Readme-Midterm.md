
# Final Project Proposal - Week 4 Update

## Introduction and Research Question

### Question: 
**How are communities connected to mining as the main industry historically changing and potentially facing displacement compared to urban areas and their surroundings?**

For the summer of 2021, I interned at a non-profit based in Colorado called [Community Builders (CB)](https://communitybuilders.org/). Their mission is to “help local leaders build healthy, equitable, and prosperous communities to improve people’s lives today and ensure a sustainable tomorrow.” I worked primarily on a values-based engagement project based in the 600-person town of Silverton, Colorado. I mostly input survey responses and then tagged them based on the values from a list of major themes and sub-themes. Throughout this process, it became clear that some of the major issues that Silverton was encountering were not unique to this town alone. On a personal level, I learned that typing up hand-written surveys and manually tagging each response is a tedious process. Because the themes that arose felt relevant to other communities in the Mountain West, it seemed useful for other communities to be able to gather this information for themselves and assess it without needing someone to do that work for them. The team at CB and I discussed turning this process into a toolkit that guides communities through the engagement process and helps them to use these values in bigger picture vision/master plans. In Silverton, CB is staying on to work on the town’s master plan, so this will give me context for how these values that are identified in this process become a part of goals, visions, and plans. 

For this project, I hope to look at some of the trends that emerged in Silverton to see how they are impacting other communities across the state, and see what geographic, environmental, and economic forces are at play that push out and disadvantage certain groups. Using data on historic mine location and rent burdened households (which incorporates the relationshp between housing cost and income), I hope to explore how the geographic isolation and lack of economic diversity of former mining towns differ from the more economically diverse urban areas and the communities that surround them. By looking at employment data by mining today compared to historic trends (still not sure what year would be a good benchmark) and analyzing the current economic conditions and demographic changes of some of those towns, I hope to demonstrate whether the more urbanized areas and towns around them might be more economically diverse and resilient to change.  

## Spatial Scope

Initially, I found that based on [this map](https://westernmininghistory.com/map/), Colorado's mining activity (both active and historic) is pretty heavily clustered in the Southwest of the state, around towns like Telluride and Silverton. These towns are located in San Miguel and San Juan Counties. There is also a cluster in the area immediately west of Denver. Based on this, I initially explored racial demographics in San Miguel and Denver Counties as my initial comparison. 

When I found my USGS historic mine dataset (linked in my data sources section below), I decided to explore the relationship between these historic mine points and rent burden as an indictor of displacement. I used American Community Survey data for the entire state to isolate counties that could be considered rent burdened. I then explored how these statewide historic mine points overlapped with these rent burdened counties. 

Next, I'd like to evaluate where mining has turned into a tourism-centered economy. I am specifically interested to see if Latinx and low-income residents are pushed out more from these small towns as they become increasingly reliant on tourism and second-home owners. It would be helpful to focus on changes in housing costs and affordability within recent years (past 5, maybe 10?), and potentially see how Covid may have exacerbated these impacts.

## Midterm Status 

Using historic mine data from a set of digitized mine features appearing in topographic maps from the USGS, I started by exploring whether these features overlapped with the counties that I had identified as rent burdened. From this initial exploration, I found that the top 5 counties that can be considered rent burdened that have the highest concentration of historic mines are Gilpin, Lake, Clear Creek, Boulder, and Gunnison counties (see my week 4 notebook to see how I found this). So these are actually some relatively urban areas in the sense that they are close to come of the main metropolitan areas (not geographically isolated mining areas). So from this it doesn’t seem that my hypothesis is true. Gunnison county is an interesting one, and there is also a spike in the data around San Miguel and San Juan counties, which were some of the original areas I had been interested in. 

There are a few thoughts that I have based on these findings. First, considering rent burden at the county level may be obscuring how some of these phenomena are unfolding for specific communities rather than for the entire county. I think zooming in on some specific towns and focusing on where their economy is now (is it mostly tourism based?), looking to see if there is a mining history (which appears to really be the case for most of the state), and seeing how the closing of that mine influenced the area ecnomically may tell me a bit more about how that town has been impacted today. Additionally, even if these towns are not displacing people more than urban areas, it is still valuable to explore how lack of economic diversity combines with a high cost of living and scarce workforce housing to see how these places are unaffordable and lead to displacement of anyone who isn't exceptionally wealthy. 

## Data Sources
USGS historic mines from digitized topographic maps:
https://mrdata.usgs.gov/usmin/ 

American Community Survey rent as a percentage of income by county

#### Further exploration: 
Potential data source/mining visualization inspiration: 
https://www.arcgis.com/apps/MapSeries/index.html?appid=6804e1bab5e840e1a3a12a7236b7a485
(Also includes an industry predominance map that may be useful to me) 

I could also potentially get industry/employment info from the Bureau of Labor Statistics: 
https://www.bls.gov/data/

This map is great (Thanks Chris) but figuring out if I can actually use it/geocode it myself and if that makes sense for the time and scope of this project: 
https://westernmininghistory.com/map/

Alternatively, this preliminary search for ‘mines’ in the “GeoLibraries” hosted by the University of Colorado Boulder has some useful data available for download as shapefiles regarding active and closed mines, federal mineral estate, material disposal sites, and others that I could use as my starting point instead (particularly the closed and active mines could be of interest):
* https://geo.colorado.edu/?utf8=%E2%9C%93&search_field=all_fields&q=mines

For demographic information, I will likely use the American Community Survey for rent burden statistics, potentially employment data as well? I'll use social explorer for that: 
https://www.socialexplorer.com/

However, the Colorado State Demographer’s office also hosts a variety of useful data including:
* County and regional data 
* Housing, jobs by sector and labor force, projections for jobs and housing, and race that would all be useful to this analysis 
* https://demography.dola.colorado.gov/data/

## Scope: Analysis and Visualizations

This was my initial scope that I think given my maps and analysis up this point will still work well: 

One map will include the locations of former mine sites and the towns associated with them for the entire state, while a series of smaller maps that concentrate on specific towns and demonstrate demographics of importance. Additionally, some charts/tables will be useful in demonstrating the changes over time that I hope to examine, such as population growth, racial demographic changes, and economic diversity.

## Insights 

For my capstone, I hope that this analysis will be helpful in supporting the toolkit. I think that demonstrating the way that the Mountain West is transforming can help support the desire for communities to perform their own an assessment that focuses on shared values and assets that can help inform goals and master planning longterm. Especially honing in on towns that are turning toward tourism, pointing out the lack of affordability and potential for displacement can point to the need for qualitative and values based planning. These spatial analyses and the potential challenges that they expose should be an important supplemental to piece to this qualitative planning approach. 

Bigger picture, it would be a goal of mine to turn this project into a piece of the toolkit, creating an app from a notebook that would allow people to interact with data and understand the trends happening in their unique communities. I am very inspired by a tool like [DistrictBuilder](https://www.districtbuilder.org/) and would love to learn to make this information interactive and accessible for people without mapping or policy backgrounds.

## Concerns

After this past week of exploring my historic mine point data and county rent burden data, I have some rethinking to do about how to explore this relationship I am interested in. I think looking at specific towns that are highly tourism dependent, evluating the presence of historic mines, and then exploring trends of lack of affordability are my next steps. How to select these towns that are geographically isolated, tourism dependent, and formerly reliant on mining? How do I determine which towns to focus on based on tourism as an economic sector? 


