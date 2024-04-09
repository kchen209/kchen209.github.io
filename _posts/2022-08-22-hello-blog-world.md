---
title: Homework 8
tags: [Technology, Blogging]
style: fill
color: secondary
description: IS445 homework8 submission
---

<div class="middle">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="Dataset" %}
</div>

<div class="middle">
{% include elements/button.html link="https://github.com/kchen209/kchen209.github.io/blob/main/python_notebooks/homework8.ipynb" text="Homework8" %}
</div>


## Write-up 1  
For the first plot that I have chosen to create and visualize, I wanted to create a bar graph and show the relationship between the representative district and the number of buildings in that district. For the code, there is a plot of x and y axis clearly shown to what I wanted it to show and the bar graph is easy to read for anyone who is interested in seeing the number of buildings in that specific district. For the color maps, there are different colors to represent each of the different district and the bars are distinct from each other so that people can know. I think that this is what is easily to be read and that is what would help make a good visualization too. For the data transformation, I wanted to count the number of buildings in the representative district so that it can show in the visualization too. This was necessary to do because the point of the plot that I wanted to show in this first plot was the relationship between the representative districts and the number of buildings in each of the districts. Other transformations, such as pivot was not used because I didn't think it would be necesscary to change any of the variables or shift them. In my Homework 7, I said "If I had more time, I would change the scales even more and even choose different variables in the dataset to look at. I want to make a visualization where it would be helpful for readers looking at this specific visualization to see that there is meaning behind it and it can be used to predict or see correlations in future homes and buildings that are being built." I think that the scales in this plot is a lot better and it was easier to read too since the interactivity was also able to help with the scaling overall.


<vegachart schema-url="{{ site.baseurl }}/assets/json/viz1.json" style="width: 100%"></vegachart>

## Write-up 2  
For the second plot that I have chosen to create and visualize, I wanted to create a scatterplot and show the relationship between the year constructed and the total number of floors a building has. For the code, there is a plot of the x and y axis clearly labled and we take the information from the dataset of the total number of floors a building has and also the year constructed. There are different colors for each of the points on the scatterplot to show each of the buildings and the number of floors that it has. This way, it would be easy to read and we can see what we need to know. For the transformations, we would aggregate using count since I wanted to count how many floors each of the buildings has and it is shown in the y-axis. I did not use any other of the transformations because I don't think it would be necessary for what I wanted the plot to show. In homework 7, I also used a scatterplot to show relationships of what I wanted to show in the plot since I know that it would be easy to read and this information overlaps.


<vegachart schema-url="{{ site.baseurl }}/assets/json/viz2.json" style="width: 100%"></vegachart>

