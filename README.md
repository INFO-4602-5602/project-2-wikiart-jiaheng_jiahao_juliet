# Project 2: WikiArt
# Group: project-2-wikiart-jiaheng_jiahao_juliet

<li>Jiahao Wang (jiwa8909@colorado.edu)</li>
<li>Juliet Anne Mcfarlane (Juliet.Mcfarlane@colorado.edu)</li>
<li>Jiaheng Zhao (jizh3194@colorado.edu)</li>

<h2>Team Member Roles: </h2>
<li>Jiaheng Zhao: First Visualization and preprocessing.</li>
<li>Jiahao Wang:  Second Visualization and Interactive.</li>
<li>JJuliet Anne McFarlane: Analyze data and visual charts.</li>

<h2>Design Process:</h2> 
As we read through the requirements carefully, we began to explore and brainstorm with the data. Based off of the data, we decided to use two interactive visualizations to present the data to the observer in the most logical manner. First, we intend to design a complex area chart, which includes the art movement of each period and the number of works. This will give viewers a broad picture of the eras. In the second chart, we are going to design a chart in which large circles consists of several small circles. The large circles represent the stylistic period for the pieces. Each small circle will represent the artistic movement. The sizes of the circles within will reflect the number of such art forms. 

  

<h2>The first visualization:</h2> 
The first visualization is an area chart. This area chart is meant to show quantitative data based on the number of artworks from each stylistic period. These periods include Renaissance Art, Post Renaissance Art, Post Renaissance Art/Modern Art, Modern Art, Modern Art/ Contemporary Art, and Contemporary Art. Each stylistic period is represented by a color and we have given viewers a key. Renaissance Art is represented by yellow. Post Renaissance Art is represented by green. Modern Art/Post Renaissance Art is represented by light blue. Modern Art is represented by red. Contemporary Art/Modern Art is represented by orange. Contemporary Art is represented by dark blue. The horizontal axis is a timeline ranging from 1400 to 2050, as the date of the artworks range from 1415-2012. The axis has increments of 50 years for clarity. The vertical axis represents the number of works in each year. To make the display of the stylistic period and numbers clear, the data was put into a two-dimensional array, which explains the differing starting points for height.
 


<h2>The second visualization:</h2> 
The large circle, which contains smaller circles within it, represents all the artwork in the Wiki dataset. There are six circles inside of the large circle. Those, similarly to the first visualization, are represented by color based on the stylistic period. What ties all of the same colored circles together is their artistic movement. For example, we can take a look at the most obvious of the groupings which is the yellow circles. The yellow circles represent the stylistic period of Renaissance Art. Throughout this period, there were three movements: Northern Renaissance, Early Renaissance, and High Renaissance. The size and transparency of these circles are responsible for telling us quantities of artworks throughout the movements. It is clear that one circle is slightly bigger and the other two are relatively the same. This is because the biggest circle is the Northern Renaissance movement, which had 144 artworks. The Early Renaissance had 73 artworks and the High Renaissance had 70 artworks, which explains their similarity in size and transparency. By clicking on a circle, it gives viewers the artist with the highest mean rating and a link in order to get more information on that artist.

<h2>Insights:</h2>
By taking a look at the first visualization, we are met with a clear visual of quantitative data. It helps us to get a better understanding of which stylistic periods were the most prominent and a better understanding of the timeline of each period. As we can see, there is overlap in the periods, which is why it is important to take a look at the second visualization for further information. However, let’s first take a closer look at the first visualization. The Renaissance Art Period is the second longest stylistic period in the dataset. For about 100 years, it has a consistent amount of artworks, but reaches its peak and dwindles down until there is an overlap with the Post Renaissance Art period. It is clear that the dwindling of Renaissance Art has a correlation with the increase in Post Renaissance Art. We can see that the longest stylistic period was the Post Renaissance Art. There is a consistent spike of artworks for the span of about 150 years within this. It ends up overlapping not only with Renaissance Art, but also with Modern Art. This period, quite obviously, has the most amount of artworks and we can see the dramatic spike in artworks before it dwindles. This period has the most overlap, as it overlaps with Post Renaissance Art, Modern Art/Post Renaissance Art, Contemporary Art/Modern Art, and Modern Art. Similarly to Renaissance Art, Post Renaissance Art, and Modern Art, Contemporary Art also reaches a peak before it dwindles. This is important because it shows that stylistic periods do not last very long and always have a strong peak before they drift off into a new period. Modern Art/Post Renaissance Art and Contemporary Art/Modern Art are both very small quantities, which goes to show that there is not much overlap in the actual style of the artworks even though there is a ton of overlap within the periods of the styles.
The second visualization is very important if a viewer wants more details on what was happening within the stylistic periods. It will give viewers some insight on what was happening during each period, how many artists were using their works in order to portray messages, and the best artist to display these messages within each movements. We can correlate the first and second visualization by looking at the amount/size of the circles and the time frame/quantity of the chart. For example, by looking at the chart, we can see that there were the most amount of artworks in the Modern Art period. Then we take a look at the circles and we can see that it has the most circles and consistently large circles. There is also a direct correlation to the amount of artworks to the amount of movements. We can also make sense of that by looking at the Modern Art Category. There were the largest quantity of artworks during that period in addition to the most movements. The circles give us a close look on the number of movements during the stylistic periods. By clicking into a circle, we can also see the artist that most impressed annotators and was given the highest mean rating. In addition, the link to view more about the artist is given. 
Renaissance Art, Post Renaissance Art, and Modern Art are growing in number, while Modern Art and Post Renaissance Art are few and far between. Each style of art has its own specific period of birth, and there will be overlapping periods when the new art style appears in the period when the previous art style is about to die.

<h2>Preprocessing:</h2> 
Use Tableau to process raw datasets, count the data by style, time, and category, and export tables that can be used directly for drawing.

<h2>Interactivity:</h2> 
(1) The interaction between the observer and the charts.
<ul>
<li>When the mouse hovers over the circles, the chart shows the corresponding style and reduces the transparency of the other styles. After selecting a category included in a style in the pie chart, the detail chart shows the artist with the highest Mean rating in the category and his information link, which jumps to the corresponding page.</li>
</ul>

(2) Interactivity between charts.
<ul>
<li>Color represents the same thing in both charts. For example, the yellow color represents Renaissance Art and so on. In both tables, the area of the color area indicates the number of works of the art category. The larger the area, the more art there is.</li>
</ul>


<h2>Accomplishment:</h2>

(1) Minimum Requirements:
<ul>
<li>One visualization must include some quantitative data.</li>
<li>One visualization must include categorical data.</li>
<li>Each visualization must be interactive.</li>
<li>Your visualizations should support at least one meaningful comparison between related data attributes.</li>
</ul>

(2) Above and Beyond:
<ul>
<li>Unusual Representations: Draw on some of the examples from class to represent data in ways beyond a typical scatterplot or bar chart.</li>
<li>Style: Keep the style consistent across all your views, with an eye towards intelligently applying visual design.</li>
<li>Interesting Tasks: Derive insight into the data. Highlight these insights in your readme and describe how the visualization enables them.</li>
<li>Integrate Imagery: Use data from the provided URLs to add more context to your visualization. For example, you could link to or scrape text about individual paintings or artists or integrate images of the art into your visualizations.</li>
<li>Coordinated Views: Have two or more visualizations that interact with one another as you move through the data.</li>


</ul>

<h2>Build Instructions:</h2>

<ul>
<li>(1)Launch a server in the root directory: python3 -m http.server 8000</li>
  
<li>(2)http://localhost:8000/index.html</li>
</ul>
  
