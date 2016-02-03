##Summary

This chart shows the average arrival delays for US domestic flights in 2014. We can see how the delay pattern develops through out the year, and how different types of delay contribute to the toal delay.We see a consistent pattern that the least chance of a delay is when you travel in April or September. The peaks are June-August and December-January. 

##Design

I'm interested to see how the average delay varies over months. I expect line chart to best represent this: x-axis will show months of year and y-axis will show the mean delay. Since we want to know how each individual delay type evolves (weather, security, etc.), there will be one line chart per individual delay type. All lines would share the same primary light blue color, except for total delay which is in black. This is to avoid distraction and differentiate between total and other delay types. 

We can see a general pattern where peak delays happen in summer/winter holidays. There may be also a compounding relationship between different types of delays. For example, a higher weather delay could also mean increased chaos in National Aviation System delay (NAS delay).


##Feedback

Feedback 1: 
it's hard to distinguish carrier and late aircraft delay > solution: used light green color for carrier delay. 

Feedback 2: 
it takes a long time to show the data, and i'm not sure what's going on > Showing a spinner to give a sense of progress

Feedback 3: 
the y axis is showing seconds which is hard to get a gut sense > convert to hours (this also makes it easier to distinguish carrier and late aircraft delay so I'm undoing what i did for feedback 1 (all sub-delays will be in blue)).


##Resources

Dataset (Jan 2014 - Dec 2014): http://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1

EDA with R
