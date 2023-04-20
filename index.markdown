---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Parking in Helsinki

If you have been to Helsinki by car, you will know the hassle of parking. Spots are notoriously hard to find and tickets are 60-80 euros.
That is a lot, especially considering that its only 4 euros an hour in the daytime in the city center, if you're lucky enough to encounter a spot. So if you are planning on driving in Helsinki, this is the page for you. We'll provide some general tips and guide yu trhough, while maybe telling you a good story along the way. By looking into the parking violations data of past years, we allow you to look up specific areas where you may want to park and show you where and when police and parking agents are the most active. We also provide a map of the city, that let's you explore parking violations and shows you where you can find paid parking lots and other stuff.


# Things you should know before driving in Helsinki

Both the police force and a corps of parking agents, often from private companies, are tasked with keeping up with motorists’ bad parking. And they do so quite a lot, a steady total of xx amount of fines have been given out in the years 2014-2017.

![fig1](/fig1.png)

The city of Helsinki deals in two types of “fines”, one is a straight forward fine and that is also the most common. They do however also have the option to simply put a notice in the windscreen of your car. More friendly than a fine, this is a reminder that you haven’t parked all that well, but you won’t get a fine! As you can see from the below plots, this notice is not widely used. But if you do get one, it will most likely be from the parking agents, the police do not bother to use these (beside 1 given out in 2014) and only deal with actuals tickets.

![fig2](/fig2.png)

But if you do want to file a complaint, you shouldn’t expect much to come from it as the vast majority of disputes are settled in favour of the parking enforcement companies.  However, if you are a tourist bringing your own car, you might be able to park in a slightly riskier manner, as the city has been mostly unable to actually get a hold of the money, when they have fined a foreign vehicle for a parking violation. A whopping 80 percent of fines given to foreign vehicles between 2012-2017 thus remains unpaid, costing the city an estimated 4,5 million Euros in lost income. 

# Still planning on taking the car?

If you remain undeterred, you've come to the right place. Because planning is gonna be important and it is worth contemplating, where you should park your car – or perhaps rather, where you really shouldn’t park your car!


# Density of the data - city center can be an expensive place to park!

![HistLongitude](/HistLongitude.png)

![HistLatitude](/HistLatitude.png)


# Bokeh

<embed 
       type="text/html" 
       src="Bokeh_Plot.html"
       width="1100"
       height="800"
       >

# Heat map of the parking tickets in Helsinki


<embed 
       type="text/html" 
       src="heat_map_Helsinki.html"
       width="800"
       height="500"
       >



Data exploration (ideas for plots etc.)

The page, pick a theme, maybe some minor aesthetics

Idea of the main interactive visualization
  how do we display this in the video?

Outline of the movie

"Are you familiar with this situation? And are you looking to avoid it in the future? Well, if you are going to be parking in Helsinki, there is good chance you will. In Helsinki around 160.000 tickets are given out each year. Luckily, we are here to help you out. By using the Helsinki parking violations data from 2014 and onwards, our magazine style blog will provide you with tips, tricks, interactive figures and maps, that helps you know where to park - and where not to park - if you want to avoid the 80 Euro fine."

"Our dataset describes the parking tickets in Helsinki between 2014 and 2017
The total size of the data is 644900 rows including basic information such as year, month, address and coordinates of the parking ticket. In addition, fine issuer, postal code, postal district area, municipality and municipality number are included."




  make sure we get it all in there: look at  https://github.com/suneman/socialdata2023/wiki/Final-Project




Sources: 
https://yle.fi/a/3-9939416 
https://yle.fi/a/3-10281783 


