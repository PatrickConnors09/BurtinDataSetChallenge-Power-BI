# PowerBI_BurtinDataSetChallenge

Chance magazine ran a contest to create a visualisation using this data set of the effectiveness of three antibiotics on sixteen strains of bacteria.
For this project we were given the data set and asked to create a visual that could fully explain the data given.

# Explanation of my thought process.

My choice of chart type is a horizontal bar chart. I chose a bar chart because I like how they display proportions and clearly separate categories from each other. I tried out some other styles but, in my opinion, bars were most effective at separating each bacteria category while also showing the MIC value. The bacteria all have very long names, but it is important that they are fully represented. I first looked at using vertical bar charts but here I thought the names seemed very hard to read. By using a horizontal bar chart, you get more room to represent each bacteria name. 

I decided to split the visualisation into three separate bar charts but all using the same y values and aligned to the same ordering. This enables me to have the charts share the vertical axis names and not having the visualisation overloaded by text. I divided each chart by antibiotic and sorted the values by bacteria in alphabetical order. I think this is important because the reader can easily compare each antibiotic’s effectiveness for each of the bacteria. The reader can just look straight across the visual to make comparisons of effectiveness between each antibiotic. 

I sorted the colours by gram staining and added these to the legend. Light purple is negative for gram staining and the darker purple is positive for gram staining. I chose to represent this by colour because it is an important categorical variable. Using these contrasting colours, it is easy to see each bacteria’s gram staining status. The visualisation shows penicillin is often ineffective on negatively gram staining bacteria in comparison with its effectiveness on positively gram staining bacteria. The reader can clearly see which colour is representative of each category by viewing the legend on the top of the graphs. 

For scale I chose a log scale, due to some values being miniscule and some being quite high. Originally when using a linear scale, it was creating really large discrepancies between the bars. This made it very hard to interpret and even see the smaller values. The log scale much better displays the proportion of each bar. Using these values closer to zero are given enough space to be meaningful while the larger value is still clearly larger proportion. The log scale is set to start at .001 and ends at 1000. 
