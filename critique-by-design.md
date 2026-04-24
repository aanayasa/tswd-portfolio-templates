| [Home](https://aanayasa.github.io/Andrea-s-Portfolio-/) | 
[Data Viz Examples](https://aanayasa.github.io/Andrea-s-Portfolio-/dataviz-examples) | 
[Critique by Design](https://aanayasa.github.io/Andrea-s-Portfolio-/critique-by-design) | 
[Final Project I](https://aanayasa.github.io/Andrea-s-Portfolio-/final-project-part-one) | 
[Final Project II](https://aanayasa.github.io/Andrea-s-Portfolio-/final-project-part-two) | 
[Final Project III](https://aanayasa.github.io/Andrea-s-Portfolio-/final-project-part-three) |

# Critique and redesign using a visualization from MakeoverMonday

## Step one: the visualization
[ Demographics of Social Media Users and Adoption in the United States | Pew Research Center](https://www.pewresearch.org/internet/fact-sheet/social-media/?tabItem=3345cffa-94a6-4e74-9272-70dee1e0e213&cb_viewport=desktop#who-uses-each-social-media-platform)

<img width="871" height="898" alt="image" src="https://github.com/user-attachments/assets/7439587b-63b4-4944-b056-a75c68dda57d" />

For my data visualization, I selected a pew research report on social media usage across different platforms based on demographics. This report caught my interest given the increased usage of social media amongst young people. I also think different platforms are beginning to merge and offer identical services, so its interesting to look at which apps are surviving this competitive field and which ones seem to be dying out or losing traction. The report had two types of visualizations, the top one is a multi-linear graph that shows which platforms adults in the U.S. report using. The first visual does not separate responses by demographics. I chose to do the second visualization which is the table that actually separates survey responses by different groups. While there were different demographics like age, gender, race/ethnicity, household income, education, community, and party ID, I chose to focus on age because it had the most stark data. Additionally, I thought this would be a good place to start given that there was a lot of creative freedom given that the original was just a table. 

## Step two: the critique

### Usefulness (5/10): 
Useful for researchers & marketing teams needing exact percentages, but lacks clear insights or guidance for broader audiences
### Completeness (7/10): 
Includes platforms, demographics, and percentages, but missing context like sample size, methodology, and benchmarks
### Perceptibility (4/10):
Table format requires scanning and calculating comparisons manually, making patterns difficult to identify quickly
### Truthfulness (6/10):
Accurately presents data, but survey limitations and potential response bias are not clearly emphasized
### Intuitiveness (3/10): 
Not easy to interpret at a glance, given several categories, the amount of numbers can be perceived as overwhelming.
### Aesthetics (2/10):
Minimal but dense and overwhelming, with little visual hierarchy or emphasis
### Engagement (2/10): 
It does not guide the viewer toward a key insight or story, nor does it invite exploration beyond scanning numbers.

## Step three: Sketch a solution

### Sketch 1:
<img width="1056" height="776" alt="image" src="https://github.com/user-attachments/assets/e1bc95ab-e733-436d-b21d-82c6b53c4090" />

My initial approach was to transform the table into a heatmap using Datawrapper to improve visual clarity and make patterns easier to identify. Visually, the heatmap is appealing and does help highlight general trends, such as higher platform usage among younger age groups and a clear decline across older groups. However, this format has limitations when it comes to comparison. While the color gradient signals differences, it does not effectively communicate the magnitude of those differences. Additionally, because all values are encoded through color rather than position or length, it requires more effort to compare across platforms or age groups. Overall, while the heatmap improved aesthetics, it is not the most effective choice for detailed comparison, thus I decided to move away from this type of design. 

### Sketch 2: 
<img width="1030" height="900" alt="image" src="https://github.com/user-attachments/assets/af1f112e-8741-465c-9dad-d74d96a6ad11" />

For my second visual, I shifted from a heatmap to a stacked bar chart to support comparison across age groups. While both designs use color, the role of color changes in this visual. Instead of representing intensity (as in the heatmap), color is now used to distinguish age groups, while bar length shows the actual values. This makes differences in platform usage more intuitive to compare.

This approach highlights the gaps in usage between the different age groups. For example, the decline in Instagram usage from younger to older groups, or the consistency of YouTube across all ages, becomes clearer because viewers can look at bar length rather than interpreting color gradients. The addition of percentage labels also makes it easier to read given that people read visuals from left to right. My goal with the title and subheading was to move beyond a neutral description and instead highlight a key takeaway for the audience. However, I found that my initial title and subheading were misaligned. Both attempted to make strong claims, but they were not fully supported or clearly connected to each other, which risked confusing the viewer rather than guiding them. Peer feedback reinforced this issue and also highlighted a lack of clarity around what the percentages represented. My peers mentioned that it was not immediately clear whether the values reflected frequency of use, preference, or survey response rates. This confusion weakens the visualization’s interpretability and credibility. As a result, in my final design, I refined both the labeling and framing of the chart. 

## Step four: Test the solution
To test my solution, I asked my peers in and out of class to critique my advice. The following questions are the same ones I asked my peers without giving them context about the visual before showing it to them. 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 
### Interview 1
- MSPPM-DA Student, peer from outside of class
- Professional & academic background in data analytics and political science 
- Feedback & Insights Different social media uses across age groups and percentages, a key finding is 18-29 uses youtube a lot, 4% of 65+ year olds use snapchat. Make the data labels on the side larger, also consider color blindness for blue you are using the same hue in different shades. 

### Interview 2 
- MSPPM DC student 
-Peer in the class 
- Little exposure to data visualization prior to this course 
- Feedback & Insights: Pretty easy to understand but title and subheading might not be completely related to what you are trying to convey because subheading is about differences in generations but the title only focuses on youtube. The key legend and color currently has the label ages in the 18-29 group but not the other. I would also include a small caption at the bottom with the source, and maybe define in the subheading or the caption what you mean by younger adults if you are only considering younger adults 18-19. Also the percentages are not clear, try clarifying if the percentages mean the people from those ages that use those platforms or if it has to do with whether they like it or not. 

### Interview 3
- MSPPM-Flagship student, peer from outside of class 
- Professional experience in consulting, and finance 
- Feedback & Insights: Stacked bar charts comparing what platforms are consumed by different age demographics to watch videos. Youtube is the most widely used platform for watching videos in comparison to other similar services such as instagram, facebook, tiktok, snapchat, and whatsapp. Nothing confusing, but surprised that youtube is the most popular and think that whatsapp or instagram would be more popular. The legend could be slightly bigger but that’s the only tweak

### Synthesis: 
A few clear patterns came up in the feedback. First, people were confused about what the percentages actually represented and how to read the legend. Second, my title and subtitle felt disconnected and a bit too “claim-heavy.” Third, readability came up a lot, things like font size, color use, and how easy it was to compare values. In the final design I change the following: 
- Made the subtitle more descriptive to clearly explain the percentages and what the colors represent
- Adjusted the title and subtitle so they align and reflect what the data actually shows
- Increased font size and kept labels on the bars to improve readability

## Step five: build the solution

<iframe title="Social Media Use Varies by Age, but YouTube Remains Universal" aria-label="Grouped Bars" id="datawrapper-chart-fA2jb" src="https://datawrapper.dwcdn.net/fA2jb/5/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="815" data-external="1"></iframe><script type="text/javascript">window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}});</script>

## References
(https://www.pewresearch.org/internet/fact-sheet/social-media/?tabItem=3345cffa-94a6-4e74-9272-70dee1e0e213&cb_viewport=desktop#who-uses-each-social-media-platform)

## AI acknowledgements
Chatgpt was used for correcting grammatical errors, suggestions to design and assistance with embedding code onto github. 

