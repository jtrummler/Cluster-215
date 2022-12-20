---
layout: default
altair-loader:
  altair-chart-1: "charts/cluster_altair.json"
hv-loader:
  hv-chart-1: ["charts/table_hv.html", 500, 500] # second argument is the desired height
---

# Philadelphia Cluster Analysis

Different neighborhoods possess different characteristics that attract potential residents to live in those places. Whether it’s the access or distance to amenities, demographic makeup, or affordability, many choices inform people’s desire to live in certain neighborhoods of a city. This web app is a cluster analysis of Philadelphia County, Pennsylvania to help inform both current residents who may be looking to move within the city, as well as transplants looking to come to Philadelphia.

# Cluster Analysis

In this map, hover over each neighborhood to learn which cluster it belongs to, and some information about what defines that cluster.

<div id="altair-chart-1"></div>



# Variable Scatterplot

In this scatterplot, hover over each point to determine the value of each variable used in the cluster analysis. You can change which variable using the drop down menu.

<div id="hv-chart-1"></div>



