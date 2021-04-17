# A4: Filterable Emissions Exploration (Albert Gerovitch)

## Design Decision Rationale
The scatterplot was chosen as the primary visual encoding to associate greenhouse gas emissions with other factors. This graph type is often used to depict correlations between variables, so the visualizaiton is intuitive for users. As an additional narrative feature, an orange color is used on the scatterplot to specifically highlight the G7 countries and draw a user's attention to these major nations. This encoding, as well as other important information, is briefly summarized at the top of the page. Additionally, as a secondary graph, a pie chart is used to depict the breakdown by emissions type for a given region. A bar graph was considered as an alternative, but would have been a less effective visual encoding, because it does not show the proportional breakdown as clearly. These visual encodings show the intended information without additional clutter or unnecessary features, maximizing the insightfulness of the exploration.

For the interaction and animation component, a user can hover over points on the scatterplot to see tooltips, filter the scatterplot in various ways, and click on the scatterplot points to update the pie chart. The tooltip was used as an intutive and easy-to-understand way of showing the user more information about a point – in this case, the country it represents. Filters were included to allow the user to narrow in on the data by year and country population, as well as to explore a variety of factors' associations with total greenhouse gas emissions. As the user changes filters, the graph updates automatically, creating interesting and revealing animations, such as the access to electricity values gradually moving upwards as the year increases. A dropdown was considered instead of a slider for year, but ultimately a slider was chosen as the easiest mode of interaction to accomplish this desired goal. Finally, to explore the data even further, the user simply clicks a point to see the emissions breakdown for a given country in the pie chart directly on the right. More complex animations were considered as elements changed in the graphs, but ultimately were not implemented to preserve the quickness and simplicity of the interactions. In this way, depending on a user's needs, they can simply glance at the plots for a quick understanding of the data, or use the various interaction and animation techniques to explore it further. This makes the exploration particularly engaging, since there are many directions to pursue with the various features, and each interaction reveals new narratives.

## Development Process Overview
Since this assignment was completed individually, the work was not split. The goals were also adjusted accordingly to create reasonable workload for one person.

The development process was relatively smooth, as there was a clear staged plan to follow. First, the basic scatterplot and then pie chart were created on the page. Then, clicking points to update the pie chart was implemented, as this was the most critical interaction technique. After that, the tooltips were added to provide additional context on the points. Finally, the filters were implemented, starting with the sliders and then the y-axis variable dropdown, to give the user even more flexibility with interactions.

In total, around 15 hours were spent developing the application. Linking the two plots to enable clicking points to update the pie chart took the most time, as many places in the code had to be updated to create this interaction technique. Getting all of the filters to work smoothly and intuitively together also took significant time.
