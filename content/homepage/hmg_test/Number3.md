---
title: "New York Neighbourhoods"
weight: 4
header_menu: true
---






To explore some of the differences the neighbourhoods in New York City might have, let's make some geoplots for visualization. We will create a map of New York containing pollution information for each neighbourhood. We will be creating a few different maps, each containing different pollution information for the city's neighbourhoods. 
The geoplots will be displayed with a dropdown menu allowing the user to switch the plot between different pollutants as well as a slider for exploring the changes in the pollution between years.

Now that we've created all these geoplots let's have a look at what they can tell us! Could it be that pollution differs from neighbourhood to neighbourhood?






{{< include-html "content/homepage/bokeh_plots/pollutants_multi_select_choropleth.html" "Looking at the plot we can see that there is definitely a hotspot of pollution in and around Manhattan. This trend remains pretty much consistent for either particle type as well as when scrolling through the years. But what could be causing this hotspot and which neighbourhoods are the ones that remain consistently highest in pollution? Let's look into some different sources of pollution to try to get a better idea on what could be causing this." >}}
In the data set we have information on both pollution due to boiler emissions as well as some traffic density information on each neighbourhood. Let's look at a geoplot of these pollutants to see if we can shed some light on the Manhattan pollution.
{{< include-html "content/homepage/bokeh_plots/traffic_multi_select_choropleth.html" " Looking at these geoplots we start to get an idea on why Manhattan is so polluted. The difference in boiler emissions when comparing Manhattan to any other borough is drastic." >}}
{{< include-html "content/homepage/bokeh_plots/boiler_multi_select_choropleth.html" "In addition, the highest amount of miles travelled is consistently in Manhattan, although the difference is not as substantial." >}}


