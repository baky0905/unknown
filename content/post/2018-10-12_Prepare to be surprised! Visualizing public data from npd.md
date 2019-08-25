---
title: "Prepare to be surprised! Visualizing public data from npd.no"
date: 2018-12-09T15:13:42
publishdate: 2018-12-097T15:13:42
image: "/images/blog/1.jpg"
tags: ["interesting"]
comments: true
---
## Experimenting with crosstalk, flexdashboard and many more...

**[Link to the web application](/html/2018-10-21-EDA-NPD.html)**

“Visualization can surprise, but it doesn’t scale. Modeling scales well, but it can’t fundamentally surprise.” – Hadley Wickham.

One of the most important phases in the Data Analysis process is data visualization. It is an inherently human activity which relies on our ability to comprehend visual information and make sense of patterns. However, there’s only so much we can spend in visualizing the data, and regardless how many hours we may decide to put into it, it is never going to be enough. Therefore, it is important to be able to build simple custom-purposed visualizations that facilitate sense-making and can trigger new ideas for modelling.

This project has started as a small-scale proof of concept for using {htmlwidgets} in R markdown. But then, inspired by awesome talk by Matt Dray (@mattdray) at #EARL2018, it took new direction incorporating new interactive features and data filtering. In this webapp Kristijan deployed interactive Rmarkdown report without help of Shiny server, using DT, leaflet, mapview, plotly, crosstalk and flexdashboard.

