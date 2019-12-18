
# Morocco
An Analysis of Morocco's Borders, Populations, and Services


## Administrative Subdivisions of Morocco
### Administrative 1 and 2 Subdivisions
Below are the first and second political subdivisions of Morocco. Morocco is a country located on the North-Western coast of Africa. Its captiol is Rabat which is the seventh capitol city to govern Morocco; however its unofficial cultural, economic, and social capitol is in Casablanca which also happens to be the largest urban settlement in all of Morocco. Poltically, it has experienced some tumultuous periods with 2011 to 2015 being a major one which led to the redistribution of political borders. 
For more reading on Moroccan political history: https://www.bbc.com/news/world-africa-14123260 

![](github3.png)

For the majority of this page, the second administrative subdivision of Tata, which is in the lower central region of Morocco, as well as the third administrative subdivision of Amerzgane which is in the Ouarzazate region of Morocco. It is directly to the North of the subdivision of Tata.

![](github2.png)
__________________________________________________

## Population in Morocco
### Administrative 1 and 2 Subdivisions by Population Predictors
Below are the same political subdivisions of Morocco with the population density separated out by each administrative subdivision. The total population of Morocco is around 35 million with a great portion of that population distributed to the North Western coastline. Part of the reason this is true is because the coast, throughout Moroccan history, has played an important role economically in terms of trading as well as culutrally in terms of culutral diffusion through the causeways of Europe and the Mediterranean. 

![](Morocco.png)
This plot includes the ranking of second administrative levels by population in the bar plot on the right as well as a corresponding color map of the same second administrative levels geographically placed in Morocco. It is clear that the majority of the population resides in the North Western corridor in the city of Casablanca with the number 1 ranking administrative subdivision in terms of population, but also in the center of Morocco. The regions of Sous-Massa-Draa as well as Marrakech-Tenesifit-Al Haouz also have a lot of people living in them-with 10.9% and 10.7% of the population respectively With the administrative subdivision of Tata and Ourzazate specifically, those are relatively low ranking 

![](mar_adm22_bp.png)
This plot does the same as the bar plot above, but with the third administratifve subdivisions which are not plotted on the map of Morocco. It breaks down each administrative 2 subdivisions by population into the administrative 3 subdivisions. The reason why Amerzgane is not visible on this bar plot is that at this point in the project I was using HDX data which is updated more frequently than GADM data, but is not as complete or consistant. This proved to be an issue for me later in the project, so after this I switched to GADM data which was older, but more consistant and easier to work with. Because of Morocco's politically tumultuous past, the borders of these administrative subdivisions do not always line up which is why Amerzgane does not appear for analysis on this graph. 

## Validation of Population Prediction
In order to validate that the predictive model of population was accurate I compared the difference, means, and logarithmic means of each administrative subdivision to the actual population raster to detemrine which model was the most accurate in the country as a whole, and with the most populous subdivision of Casablanca as an example. 
![](added_R_Fit.png)
![](density_plot_MAR.png)
![](correlation_plot_Mar.png)

![](10.png)![](9.png)![](5.png)![](1.png)![](2.png)![](3.png)![](8.png)![](6.png)

Overall, the Difference of Sums was the smallest error number therby indicating that this predictive model was the closest to the actual population and therefore the most accurate. 

In Casablanca itself, the predictive models utilizing the bandwidth tended to overestimate the suburbs while underestimating the innercity. This could be mitigated by a machine learning algorithm such as random forest or gravity models. 
___________________________________________________
## Access to Healthcare and Roads as Determined by Topography
![](access_throughout.png)




