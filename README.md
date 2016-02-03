##Summary

This chart shows the average arrival delays for US domestic flights in 2014. We can see how the delay pattern develops through out the year, and how different types of delay contribute to the toal delay.We see a consistent pattern that the least chance of a delay is when you travel in April or September. The peaks are June-August and December-January. 

##Design

I'm interested to see how the average delay varies over months. I expect line chart to best represent this: x-axis will show months of year and y-axis will show the mean delay. Since we want to know how each individual delay type evolves (weather, security, etc.), there will be one line chart per individual delay type. All lines would share the same primary light blue color, except for total delay which is in black. This is to avoid distraction and differentiate between total and other delay types. 

We can see a general pattern where peak delays happen in summer/winter holidays. There may be also a compounding relationship between different types of delays. For example, a higher weather delay could also mean increased chaos in National Aviation System delay (NAS delay).


##Feedback

Feedback 1: 
it's hard to distinguish carrier and late aircraft delay > solution: used light green color for carrier delay. 




Please help me improve this visualisation. You may want to think along these lines:

*What do you notice in the visualization?

*What questions do you have about the data?

*What relationships do you notice?

*What do you think is the main takeaway from this visualization?

*Is there something you don’t understand in the graphic?


##Resources

Dataset (Jan 2014 - Dec 2014): http://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1

EDA with R

