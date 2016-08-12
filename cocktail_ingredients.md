## Summary

This data vizualization shows all the liquid cocktail ingredients used in cocktails 
(featured in the menu) at Union Lodge #1 in Denver, Colorado. The chart provides a 
comparison of the ingredients used. The viewer can see what is used most, 
what is used in small quanity, and what is not used at all in cocktails featured 
on the menu (like vodka...there is none at Union Lodge #1). The volume in mL is 
calculated by adding up the total volume of a particular ingredient used across all 
cocktails in the menu. 

### Design

My first idea was to create a chart using circle packing. I put together a draft using [RAW](http://app.raw.densitydesign.org/#%2F)
Here it is: https://codepen.io/Jomonsugi/pen/ZOvRak

I am a complete beginner to html, css, svg, d3, and dimple.js, so after looking
at the intricacy of the code I would need to write (and understand) in order to 
produce a nice looking circle packing chart (that is interactive), I decided to go 
with a bar chart instead. I am interested in continuing my learning on data visualizations,
however I believe in building on fundamentals and fully understanding the code
I am using before advancing to more complicated models. 

The bar chart does suit my data and the comparison's I wanted to communicate.
After shifting to a stacked bar chart with some interesting options available through
dimple and d3, I think the chart is interesting, informative, and fun to play with. 

The goal of the chart is to give the viewer an understanding and comparison of the types 
of the liquid ingredients used in the menu cocktails at Union Lodge #1. Past that I wanted
more information available through the visualization and through feedback, I found out others
did as well. The interactive features served this purpose. The tooltips offer more information 
for those who want it.

I made a few edits to the visualization based on feedback that I received
from others: 

* I divided the bars to show the distribuation of ingredients that make up 
the total volume of an ingredient, based on the cocktail they are used in 
* I added a tooltip that shows the type of ingredient
* I rotated the ingredient labels 45 degrees 
* I edited the 'Types' variable to give a clearer explanation

Other edits I made based on my own observations:

* I increased the font sizes of axis labels and ingredient labels
* I made the title/subtitle clear (with more explanation)
* I changed ounces to mL

### Feedback

I collected feedback throughout various stages of producing my chart. 
Each person returned their feeback in differnt forms, which I have kept relatively intact below. 

I sent my first draft to my friend **Bryce**, who works for an oil and gas company. 
His knowledge of cocktail ingredients is above average. 

1. What do you notice in the visualization?

 > I notice how many ounces of liquid go into the total amount of drinks at the bar. (if every drink was made one time, 
 > this visualization shows how many total ounces of each ingredient would be used)

2. What questions do you have about the data?

 > I want to know the distribution of these liquids in to the total number of drinks. 
 > I want to know actual ounces and not rounded ounces

3. What relationships do you notice?

 > I'm not sure I notice any relationships. I don't know what conclusions I should draw. There is probably a relationship between the 
 > number of drinks an ingredient is featured and the total number of ounces in which the ingredient is used on the entire menu, but I > hesitate to make draw that conclusion b/c I know that some ingredients are used in very small amounts in a great many drinks.

4. What do you think is the main takeaway from this visualization?

 > Gin and Rye are the most popular base spirits on the menu. This is interesting to note. Without seeing the visualization I would 
 > have assumed that bourbon would be used more than rye. 

5. Is there something you don't understand in the graphic?

 > I think I understand what the graphic is visualizing. 

I also sent the first draft to my girlfriend, **Emily**, who was probably way too nice to me...

1.) 
 > A clear understanding of the amount of cocktail ingredients for Union Lodges inventory by ounces demonstrated through a bar chart.

2.) 
 > I have no questions, it's very easy to understand.

3.) 
 > Ounces to ingredients.

4.) 
 > This visualization is easy to quickly takeaway the greatest amount of ingredients to the least amount. 

5.) 
 > No.

After taking these comments into account, I edited and sent a draft to my friend **John**, 
who primarily does illustrations for bands. 

> I think this looks really good and is totally intuitive and reads clearly. I always have a hard time reading text that’s straight 
> down at a 90 degree angle, it’s a minor thing, but, if you could put them all at a 45 degree angle or something, that might help 
> (also understood if that’s not an option). My takeaways were that I didn’t know Gin and Rye were so common, the Soda being so 
> prevalent is not a surprise. The little animation drawing a line from the cocktail to the Y axis is nice and helpful. 

> I hope some of the feedback is somewhat helpful, not sure exactly what you’re looking for, but, I think this looks great, makes 
> sense, and is easy to understand. If I were handed this on a project, I would be able to use it to make an illustration or find some > sort of conclusion/idea from it (if that makes any sense). 

I then sent the chart to my friend **Chad**, who is a data analyst and produces a lot of data visualizations for high profile clients. 

* What do you notice in the visualization?

 > Ingredients that are used in small amounts tend to only have a single use, while ingredients 
 > that are used in large quantities tend to be used much more often.
 
* What questions do you have about the data?

 > It'd be interesting to see the same chart but with the cocktails on the x-axis rather than ingredients.
 
Note: If I put the cocktails on the x axis, then each bar would represent how many mL is in each drink
and then I could divide the bars to show the makeup of each cocktail. This would be interesting if you 
wanted to know more about what is in each drink, but my chart isn't a recipe book, it is about showing and 
comparing the types of ingredients used at the bar. 
 
* What relationships do you notice?

 > Soda and lemon juice are the most used non-alcoholic ingredients.
 
* What do you think is the main takeaway from this visualization?

 > Gives you a good idea of how much ingredients you need to buy for a given cocktail menu.
 
* Is there something you don’t understand in the graphic?

 > I don't know what 50% of the ingredients are.


Each person that gave me feedback spurred me to make edits that directly took into account the 
feedback I received. Their feedback also helped me to think about others perceptions of my chart, 
which brought about edits of my own. 

I believe this chart would be most interesting to those who are bartenders or cocktail enthusiast, however
I still wanted to make a chart that was accessible to the broadest group of people possible. 

### Resources 
My primary resource was the Udacity forums

Past that I used a lot of webpages that helped me out:
http://nestacms.com/docs/creating-content/markdown-cheat-sheet

http://assemble.io/docs/Cheatsheet-Markdown.html

https://github.com/PMSI-AlignAlytics/dimple/issues/156

http://learnjsdata.com/read_data.html

http://dimplejs.org/

http://dimplejs.org/adhoc_viewer.html?id=adhoc_bar_custom_tooltips

http://stackoverflow.com/questions/17791926/how-to-rotate-x-axis-text-in-dimple-js

http://www.perceptualedge.com/articles/visual_business_intelligence/rules_for_using_color.pdf

http://app.raw.densitydesign.org/#%2F










