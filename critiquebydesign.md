# Critique By Design
The following graph represents the statistics of the women's world cup soccer teams from 1969 to 2020. The link for the following graph can be found [here](https://observablehq.com/@cassiead/cse-442-a2). The title of the graph I selected is "Total Goals Scored in International Competition While Home (1969-2020)". 

<img width="419" alt="da9f17e7c079bc54fd1be552e44b0a989f5f5b7fd75cb397915c253c298632b7ba6d2cb40ecb52640507dca48a4cd604c3f4461ddadc2583b3a628d8d4e64593" src="https://user-images.githubusercontent.com/117240476/202291989-ae035911-8699-4db5-a1d0-bfeab6801cb8.png">

I decided to pick this visualization because I am passionate about soccer, and the world cup is just around the corner, which made it an excellent choice to discuss. Usually, we associate soccer and sports with men. Still, I wanted to include an analysis of how women perform in this sport and the team leading throughout history. 

## Critique the visualization

Initially, I quickly analyzed the visualization and identified what impacted me the most. It was hard to grasp what the author intended with the graph. There were a lot of things going on at the same time. I noticed three charts in the exact visualization, but I needed help picking one that explained the author's intention most. Then I read the title, trying to figure out what the graph was about. I needed clarification because the title only related to some of the graphs displayed. On the other hand, I liked that the author used a bar chart to say frequencies, which is a very intuitive way to compare world cup teams. 

After the quick inspection, I used Stephen Few's guide to evaluate the visualization in more detail. This strategy helped me better understand what things could be improved from the graph by analyzing aspects of usefulness, engagement, intuitiveness, etc. That made me realize that another thing that needed to be more intuitive about the chart was the order of the bars. As you can see in the picture above, the values aren't sorted by importance, which makes it harder to associate and evaluate which team is better at scoring goals. Additionally, the use of three graphs isn't adding more information but needs to be clarified which one is more important and how they relate to each other. The objective of a chart is to reduce the work done by the user, digesting as much as possible the data presented. Furthermore, I realized that the name of the third graph needed to be more precise about the measured values. Finally, I felt the colors were overused, making it look like a rainbow chart.

## Wireframe a solution

![Sketch](https://user-images.githubusercontent.com/117240476/202293926-70a8f9b0-67c9-4b83-bc18-af0e3edeb9bf.jpg)

## Test a solution
After creating a sketch of the proposed visualization, I tested my proposal with a student with a background in numbers and an adult who didn't know about managing and plotting data. The questionary I used to collect the data is the following: 

1. What is the graph about?

2. Can you describe to me what is it telling you?

3. Is there something that impacts you?

4. Is there anything you find confusing or hard to understand?

5. Who do you think is the intended audience for this?

6. Is there anything you would change or do differently?

The answers I collected from the questionary are the following:

Student, mid 30's

1. The graph shows the goals per country, though i am wondering if its the average number of goals?
2. The graph tells me NZ,KP,BR and JP have the highest number of goals out of all countries.
3. I like the focus given to the first 4 countries and that a vivid color is used to emphasize on its importance, since the rest of the countries have a gray color.
4. I find it hard to understand how was the number of goals per country calculated.
5. The audience for this graph are soccer fans who might be curious of goals per country taking into account the timeframe.
6. Something that might be tried is a bubble chart or some graph of the sorts that shows the changes per year.

Adult, mid 30's

1. The graph shows the best four countries in women's soccer scoring goals when playing at home. 
2. The graph tells me that the highest scores per match in countries playing women's soccer are NZ, KP, BR, and JP. 
3. I am impressed with the difference in goals scored between the top two and the rest. But I should have been interested in comparing them with the rest of the countries.
4. I need help understanding the acronyms of the countries.
5. The audience is soccer fans interested in knowing the best or best attackers in women's soccer international matches per country. 
6. I would only group the data in some of the years because it can be that there are countries that are getting better at soccer.

After reading the responses, I had new changes, including the graph. Sometimes the first approach to the graph could be better. The first thing I changed is that instead of a bar chart, I chose a scatter plot that compared two variables: games played and goals scored. Each point represents a country. The graph shows the relationship of goals to games played, in a sense that you can identify which teams are the ones that play more and have high total scores, the ones that score a lot but don't play that often, the ones that play a lot but don't have high scores and finally the ones that don't score and don't play too much. Eventually, the graph will filter between the dates the user wants to compare, allowing them to find the best or most famous teams at specific times in history.   

### New Sketch

![Untitled Notebook-2 2](https://user-images.githubusercontent.com/117240476/202333004-32543981-c9cf-49de-ac02-f483c10b7e29.jpg)

## Build your solution

<div class='tableauPlaceholder' id='viz1668650419009' style='position: relative'><noscript><a href='#'><img alt='Best Attackers and Most Famous Women Soccer Countries While Playing Home ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WomenSoccerCountries&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WomenSoccerCountries&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WomenSoccerCountries&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1668650419009');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

I picked this graph because it better depicts the relationship between the games and the goals scored by the countries. Most of the recommendations I got from the people were that it took a lot of work to understand the average goals scored per match, and it would be helpful to compare them with the rest of the countries and not only with the top 10. Another insight the questionary gave me was that instead of aggregating all the years, it would be helpful to filter them manually and understand how team quality improved or worsened in history. 

I tried to express a story about which countries stand out from the rest by scoring many goals or playing many matches. You can see a trend in the data that the most famous and best countries are highlighted in the graph. I showed the new chart in class, and people thought it was more intuitive and easier to understand and analyze how good a country is compared with the rest. 


## Reference
Cassie Duong (October 27, 2020) "CSE 442 A2 Analysis Questions". Retrieved: November 13 2022 from https://observablehq.com/@cassiead/cse-442-a2
