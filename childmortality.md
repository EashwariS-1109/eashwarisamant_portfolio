# Critique By Design - MakeoverMonday

This project explores the critique by design technique to improve an existing data viz and unearth the story that lies within.

## Design Process
### Explore - Finding a viz with a hidden story
Step one of the project was finding a data viz on the Makeovermondays website. For me, this viz had to be a blend of three things - a topic I'm passionate about, built upon a complex dataset, and something that could benefit from a revamp. Essentially, it had to be a story worth sharing with the world.

### Examine - Actionable Critique
It's easy to critique, but much harder to improve. This is why in step two, I began to deconstuct and dissect the chosen viz using Stephen Few's Data Visualization Effectiveness Profile. This critical analysis helped me identify the pros and cons of the current viz; what's working, what isn't and most importantly - WHY! Next, I built simple pen-to-paper sketches to see how things could be done differently. At this stage, it was low fidelity execution, high fidelity critical thinking! 

### Evaluate - Relooking at the data, with an external lens
I think data is a language, and languages are a medium of communication. Visualizations don't exist in silos. They are meant to synchronize minds and hearts. This is why, user research was critical to evaluate the sketches and prototypes I built. I conducted semi-structured interviews with five different participants where they engaged with my versions of the viz. I then synthesized user feedback to draw insights and go back to the drawing board.

### Elevate - Re-telling the story
Finally, it was time for high fidelity execution and pixel perfection! It was time to showcase the story I unearthed from the previous viz and present it in a new light!

## Let's dive into each of these steps!

## EXPLORE
From the MakeoverMonday website, I picked the 'Child and Infant Mortality' data viz produced in September 2024 by 'Our World in Data'.

<iframe src="https://ourworldindata.org/grapher/child-mortality-gdp-per-capita?time=2021&tab=chart" loading="lazy" style="width: 100%; height: 600px; border: 0px none;" allow="web-share; clipboard-write"></iframe>

This viz fit my criteria perfectly - it presented healthcare related information (something I'm passionate about), it was built upon a complex data set (per capita GDPs of all nearly all the countries in the world, respective child mortality rates and populations across the years of 1950 to 2022) and lastly it was something that could benefit from a revamp. Child mortality is a crucial issue in today's world as income and health inequity rises across the globe. Currently, the viz did not produce an instant aha! moment or even give an at-a-glance insight to someone who looks at it. This is where I began to......


## EXAMINE
Using Stephen Few's Visualization Effectiveness profile, I dissected the viz and ranked it across the following key parameters - 
#### Informative Parameters - Usefulness, Completeness, Perceptibility, Truthfulness, Intuitiveness
#### Emotive Parameters - Aesthetics, Engagement

Here's a sneak peak into my critique!

![Child Mortality OG Viz](/childmortalityoriginalviz.png)

#### What worked, What Didn't and Why?
The critique method helped form a comprehensive evaluation of the viz. While the visualization has its strengths, particularly in terms of data integrity and completeness, it falls short in areas like engagement and perceptibility. Overall, I think the viz presents data around the really important and useful topic of child mortality. Child mortality is tied to the world's future and humanity's future as a whole. What stood out to me was that it compared three really distinct factors - countrywise population, mortality rate and per capita GDP. The interplay of these three factors is really interesting because there may be underlying causal relationships between per capita GDP and child mortality due to the confounding variable of 'healthcare spending' of each country. I think what worked really well was the binning of the x and y axes. I found myself looking at the viz in a quandrant method. I looked for the top left - poorest countries with high mortality rates and the lower right - richest countries with lowest mortality rates. I would go ahead and actually try to turn it into four quandrants and use a monochrome palette to show the saturation on the two extremes. This could be a wonderful way to show healthcare inequality. I think what didn't really work well, or rather slowed down my process of understanding the viz was the overuse of colors and the lack of a title. The viz uses too many categorical colors and that too in a scatter plot where the sizes of the dots are affected by the parameter of population. This makes it really hard to register country-to-dot association, and even just notice the smaller dots. If I had to change three things only, here's what I would do. 1) I would change the title to something a lot more contextual. If my audience was the World Health Organization, I would use the title to draw attention to the top left - "It's 2021. African children should be living longer than they are!" 2) I would use the color red to draw attention to specific geographies and highlight the extremities on the viz. 3)I would allow the audience to comapre only two out of the three parameters at a time, making the comorehension a lot easier. I would explore hwo to do this in either a chloropleth map or a heat map form.		
		
#### Key Strengths
Data Integrity - The visualization is based on a reputable UN data source, enhancing its credibility.            
Completeness - It provides all necessary information, including axis labels, tooltips, and a legend.         

#### Key Weaknesses
Perceptibility - The excessive use of colors and categorization creates visual clutter, hindering immediate understanding.       
Usefulness - The lack of a clear title and focus on correlation rather than causation limits its insights.       
Intuitiveness - The scatter plot format, combined with population-based dot sizing and continent-wise coloring, makes it difficult to navigate.       
Aesthetics - The current color scheme and font choices can be improved for better readability and visual appeal.        

#### How can I make it better?

Simplify and Focus     
Clear Title - Writing a concise and informative title that highlights the main message.     
Reduce Color - Using a monochrome color scheme or a limited palette to improve readability.      
Prioritize Insights - Focus on the key correlation or causal relationship between GDP and child mortality rates.     

Enhance Visual Clarity     
Choose Appropriate Chart Type - Using a chloropleth map, heatmap, or bar graph for better visualization of geographical data.      
Optimize Dot Sizing - Exploring alternative methods for representing population size, such as different dot shapes or sizes that are more visually intuitive.     
Improve Labeling - Reducing redundancies and visual clutter by hiding or de emphasizing labels wherever necessary.    

Enhance Engagement     
Tell a Story - Incorporating a narrative or storytelling element to connect the data with the deeply emotional issue of child mortality.      
Highlight Key Findings - Using annotations or callouts to emphasize important trends or insights.     

By addressing these areas, the viz can become more effective in communicating its message, engaging its audience, and providing valuable insights into the relationship between GDP and child mortality rates.


### Key Takeaways from the Critique
Having three parameters of GDP, mortality rate and country wise population interplaying together was doing the viz more harm than good. The over categorization by color and dots - through countries, continents and across the years of 1950 to 2022 was overwhelming as a audience. To curtail this overwhelm, I decided to work with the subsection of the 2021 dataset. I conducted user interviews to get an external and objective perspective on whether or not I should remove either the population or GDP parameter from the interplay.

User research for information design was a novel experience. And it also gave me a great break from looking at multi-colored dots that were now starting to hypnotize me from looking at them for too long!


## EVALUATE
At the end of the critique, I went back to the drawing board to create my own iterations of the viz. Below are a few sketches I created to explore how the same data can be visualized in a more stylized, and abstract density graph, a treemap and a quandrant map.

[Iteration1](childmortalityv1.png)
This iteration was meant to be a more abstract, graphical representation using a density graph. 

[Iteration2](





