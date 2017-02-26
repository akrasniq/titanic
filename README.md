### Titanic - Survivors and Casualties by Gender and Passenger Class

#### Summary
I will be visualizing the Titanic Data. More specifically, I will show a summary of survivors and casualties based on Passenger sex, and Passenger Ticket Class.

#### Design
For my chart design I decided to use a bar plot because it is easy to interpret and it does a good job of highlighting comparisons (differences) between categorical data. In my case I wanted to draw attention to the Passenger Class (my x variable) and the corresponding Survival or Casualty count (my y variable). The bars for each category are stacked, because I wanted the viewer to immediately see the total number of passengers who survived or died. In addition I decided to color my bars with 2 difference color hues to draw attention to the gender of the passenger. The plot also contains a legend describing the meaning behind each color. I also wrote a custom ToolTip to highlight information such as Gender, Survived/Died indicator, Count and Ticket class that I thought would help the user understand my points. 

Per my reviewer feedback and additional personal ideas I changed the plot quite a bit from its original state. Here are some of the major changes I made
- Originally started with 2 plots, one highlighting survivors and the other highlighting casualties. For my final submission I decided to combine survivors and casualties in one plot, as I thought 2 plots added a bit of confusion. Survivors are represented in the Positive y axis, and Casualties are represented in the Negative y axis.
- Scaled the y axis to a max of 400 and min -400. This was done because the number of casualties is far greater then survivors and not scaling led to bar lengths that were misleading.
- Added a legend to the plot
- Wrote a custom ToolTip to contain better descriptions.
- Renamed the axis with clear titles
- Renamed the pClass variable to read Passenger Class.


#### Feedback

##### Reviewer 1

**What do you notice in the visualization?**<br>
	I notice the titles of the graphs, the 2 different graphs, and that the graph is interactive.
**What questions do you have about the data?**<br>
	What is pclass? 
**What relationships do you notice?**<br>
	I noticed the relationship with class and deaths for men. In other words, that the higher the 'p class' the more men died.
***What do you think is the main takeaway from this visualization?***<br>
	I think the main takeaway from this visualization is that more women survived the Titanic catastrophe than men. 
***Is there something you don’t understand in the graphic?***<br>
	No, everything is easily comprehensible. 


##### Reviewer 2
**What do you notice in the visualization?**<br>
	The plot is interactive
**What questions do you have about the data?**<br>
	what is Pclass, what is "Survived:1" vs "Survived:45"?
**What relationships do you notice?**<br>
	Pclass, sex and survival/death odds
***What do you think is the main takeaway from this visualization?***<br>
	Passenger Class and Sex seem to have played a role in Survival/Death odds
***Is there something you don’t understand in the graphic?***<br>
	I'm a little unclear on the legend of the chart. What's represented in the x-axis? Do I need to understand what Pclass is?
	
##### Reviewer 3
**What do you notice in the visualization?**<br>
	I noticed more female survivors than male. furthermore, more male deaths than female. 
**What questions do you have about the data?**<br>
	my question is, what does the x-axis represent? it's not clear what pclass means? 
**What relationships do you notice?**<br>
	Looks like more male deaths in pclass 3 than 2 or 1. not sure what that means? maybe pclass represented lower income class, which may mean that they received less priority than upper class? 
***What do you think is the main takeaway from this visualization?***<br>
	Nice and simple. I think a legend would be nice. 
***Is there something you don’t understand in the graphic?***<br>
	Looks clear enough. Perhaps more description of the pclass definition. 

#### Resources
https://www.udacity.com/
http://dimplejs.org/