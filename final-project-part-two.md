| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards

## Visual 1: NCAA Historical Gap 
For my first visualization, I wanted to show the long-term trend in NCAA championship viewership. Originally, this was one combined visual, but after receiving feedback, I separated it into two charts. The first chart highlights the historic gap between men’s and women’s championship viewership, while the second focuses on the crossover moment where women’s viewership intersects with, and surpasses, men’s viewership.

<div class="tableauPlaceholder" id="tableau-ncaa-crossover" style="position: relative;">
  <noscript>
    <a href="#">
      <img
        alt="NCAA historic crossover moment"
        src="https://public.tableau.com/static/images/NC/NCAAHistoricGap/NCAACrossOver/1_rss.png"
        style="border: none;"
      />
    </a>
  </noscript>

  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="NCAAHistoricGap/NCAACrossOver" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="no" />
    <param name="static_image" value="https://public.tableau.com/static/images/NC/NCAAHistoricGap/NCAACrossOver/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("tableau-ncaa-crossover");
  var vizElement = divElement.getElementsByTagName("object")[0];

  if (divElement.offsetWidth > 800) {
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
  } else {
    vizElement.style.width = "100%";
    vizElement.style.height = "600px";
  }

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Visual 2: NCAA Historic Crossover 

<div class="tableauPlaceholder" id="tableau-wnba-growth" style="position: relative;">
  <noscript>
    <a href="#">
      <img
        alt="WNBA growth in attendance and viewership"
        src="https://public.tableau.com/static/images/vi/visual1_17760241540270/Dashboard12/1_rss.png"
        style="border: none;"
      />
    </a>
  </noscript>

  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="visual1_17760241540270/Dashboard12" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="no" />
    <param name="static_image" value="https://public.tableau.com/static/images/vi/visual1_17760241540270/Dashboard12/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("tableau-wnba-growth");
  var vizElement = divElement.getElementsByTagName("object")[0];

  if (divElement.offsetWidth > 800) {
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
  } else {
    vizElement.style.width = "100%";
    vizElement.style.height = "600px";
  }

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Visual 3: WNBA Viewership Boom 
The main challenge I ran into was that these two trends were on very different scales. Viewership was in the hundreds of thousands, while attendance remained much lower due to smaller venue capacities. Even though attendance increased, it did not appear as significant when compared to the scale of viewership.

Originally, I tried combining both in an area chart, but it felt misleading and visually overwhelming. The difference in scale made it difficult to interpret either trend clearly. Thus, I made the decision to focus solely on viewership, since it tells a stronger and more compelling story about growth and visibility. I kept the area beneath the line to emphasize that upward trend without overcomplicating the visual.

<div style="margin: 20px 0;">
  <iframe 
    title="The WNBA Viewership Boom"
    src="https://datawrapper.dwcdn.net/9ZujH/3/"
    scrolling="no"
    frameborder="0"
    style="width: 100%; height: 600px; border: none;"
  ></iframe>
</div>

## Visual 4: Pay Disparity 

The pay disparity visual was one I went back and forth on a lot. I knew from the start that a bar chart would be the most effective way to show the difference, but I wanted to present it in a more creative and engaging way. My initial idea was to use a pictograph with basketballs as the units. However, the platforms we were working with were not well-suited for this type of design, and it proved difficult to implement in Tableau.

As a result, I used generative AI to create the visual. I specified the dimensions, chart type, and data I wanted to display, allowing me to build the pictograph more precisely. Since the original data compared salaries in the millions to those in the hundreds of thousands, representing this literally would have required an unrealistic number of icons. To address this, I scaled the data so that each basketball represented $100,000. I then divided each salary by 100,000, which resulted in approximately 13 basketballs for the NBA and 2.5 for the WNBA. This allowed me to clearly communicate the disparity while keeping the visual readable and intuitive.

<img width="1536" height="1024" alt="ChatGPT Image Apr 21, 2026, 10_33_06 PM" src="https://github.com/user-attachments/assets/520de9c3-5141-4d1d-9b32-129cd713ee4f" />


## Visual 5: Revenue Court Split 

The split court was an idea that remained consistent even after my initial sketches. The main challenge was finding a platform that could effectively execute it. Similar to the pictograph, working with icons in traditional tools like Tableau proved difficult. To overcome this, I moved the design into Figma, where I uploaded both my data and sketches to build the visual more intentionally.

It was important for me to include three separate courts: one representing the NBA model, one showing the previous WNBA CBA, and one illustrating the new agreement. This structure allows for a clear comparison across systems. Rather than focusing on absolute dollar amounts, this visual shifts the focus to how revenue is distributed, highlighting the structural differences in pay. Ultimately, it emphasizes that the issue is not just about how much players earn, but how revenue is split and what constitutes a fair share.

<h2>Visual 5: Revenue Court Split</h2>
<div style="max-width: 900px; margin: 24px auto;">
  <img 
    src="https://github.com/user-attachments/assets/2c942832-a4e8-4c13-81cb-564d9d1bf7da" 
    alt="NBA revenue split court"
    style="width: 100%; height: auto; display: block; border-radius: 12px;"
  >
</div>

<div style="max-width: 900px; margin: 24px auto;">
  <img 
    src="https://github.com/user-attachments/assets/77ea76b9-9b59-4680-93e4-04c0e1d74d90" 
    alt="WNBA previous CBA revenue split court"
    style="width: 100%; height: auto; display: block; border-radius: 12px;"
  >
</div>

<div style="max-width: 900px; margin: 24px auto;">
  <img 
    src="https://github.com/user-attachments/assets/6c3399ab-43e4-4e09-a989-a5d5a3882419" 
    alt="WNBA new 2026 CBA revenue split court"
    style="width: 100%; height: auto; display: block; border-radius: 12px;"
  >
</div>

## Visual 6: CBA Max Salaries Throughout the Years
This visual was not part of my original sketches in its current form. Initially, I had designed a growing bar chart to show changes in revenue percentages over time. However, I realized that the split court visuals already communicated that story effectively.

Instead, I shifted my focus to how CBA agreements have impacted actual Supermax salary outcomes. I split this into two visuals that track changes in supermax salaries over time. The first provides historical context, showing how salaries evolved under previous agreements after each time a new CBA contract was negotiated. The second isolates the 2026 CBA by greying out earlier years and highlighting 2026 in bright orange. This contrast emphasizes the magnitude of the increase and makes the shift in compensation immediately visible.

<div class="tableauPlaceholder" id="tableau-cba-part2" style="position: relative;">
  <noscript>
    <a href="#">
      <img
        alt="CBA salaries throughout the years (part 2)"
        src="https://public.tableau.com/static/images/cb/cbasthroughouttheyears/cbapart2/1_rss.png"
        style="border: none;"
      />
    </a>
  </noscript>

  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="cbasthroughouttheyears/cbapart2" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param name="static_image" value="https://public.tableau.com/static/images/cb/cbasthroughouttheyears/cbapart2/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("tableau-cba-part2");
  var vizElement = divElement.getElementsByTagName("object")[0];

  if (divElement.offsetWidth > 800) {
    vizElement.style.width = "1100px";
    vizElement.style.height = "627px";
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width = "1100px";
    vizElement.style.height = "627px";
  } else {
    vizElement.style.width = "100%";
    vizElement.style.height = "727px";
  }

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Visual 7: CBA Max Salary 2026 Deal 

<div class="tableauPlaceholder" id="tableau-cba-salaries" style="position: relative;">
  <noscript>
    <a href="#">
      <img
        alt="CBA max salaries throughout the years"
        src="https://public.tableau.com/static/images/cb/cba2026/newdeal/1_rss.png"
        style="border: none;"
      />
    </a>
  </noscript>

  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="cba2026/newdeal" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param name="static_image" value="https://public.tableau.com/static/images/cb/cba2026/newdeal/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("tableau-cba-salaries");
  var vizElement = divElement.getElementsByTagName("object")[0];

  if (divElement.offsetWidth > 800) {
    vizElement.style.width = "1100px";
    vizElement.style.height = "627px";
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width = "1100px";
    vizElement.style.height = "627px";
  } else {
    vizElement.style.width = "100%";
    vizElement.style.height = "727px";
  }

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


# User research 

## Target audience

### 1. The Newcomer
People who may recognize players like Caitlin Clark or Angel Reese but lack context about the WNBA or pay equity.

- Why they matter: They test whether the story is clear and accessible.
- Goal:Move them from unaware about this issue to informed by showing the growth and impact of investment in women’s sports.

### 2.Superfans 
WNBA fans, or sports fans, or those familiar with pay equity conversations.

- Why they matter: They evaluate credibility and can tell if this tells the honest story of pay inequity and where data might not make sense. 
- Goal:Provide insightful feedback, while also getting more specific critique to this issue area.
  
### 3. Data-focused Audience
People interested in data visualization but not necessarily sports.
- Goal: Get unbiased feedback from people with no sports knowledge but have knowledge on data visualizations and can provide honest, precise critique that comes from experience. 

## Interview script
> List the goals from your research, and the questions you intend to ask. 


## Interview Script

| Goal | Questions to Ask |
|------|------------------|
| Understand first impressions | At a glance, what is the first thing you notice about this visual?<br>What is this visual about? |
| Evaluate ability to identify trends and key data | Can you define a trend that's going on here?<br>On a scale of 1–10, how easy was it to find the key data points on this graph?<br>What are your main takeaways from this visual?<br>Is there something on here you wish you had more information on? |
| Assess clarity and design (aesthetics) | Are the sizes of text, lines, and shapes a good size, too big, or too small?<br>Do the colors fit well with the story?<br>Are the images distracting?<br>Do you think this is an appropriate visual to showcase the information?<br>If not, would there be another graph that would help you understand this better? |
| Evaluate understanding of the story and impact | Can you identify what the main story or issue of the graph is?<br>What kind of story is it telling?<br>Does this change the way you think about the WNBA, women’s sports, or pay equity? |

## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

## User Feedback Table

| Questions | Interview 1 (Visuals 4 & 5: Pay Disparity + Revenue Courts) | Interview 2 (Visuals 4 & 5: Pay Disparity + Revenue Courts) | Interview 3 (Visuals 4 & 5: Pay Disparity + Revenue Courts) |
|----------|-------------------------------------------------------------|-------------------------------------------------------------|-------------------------------------------------------------|
| **At a glance, what do you think of these visuals?** | The court visual is really creative and stands out, and the basketball chart is easy to understand quickly. | Both visuals are very intuitive. I immediately understood that it was about pay differences and revenue splits. | The visuals are engaging and easy to read, especially the court and basketball ones. They stand out compared to the others. |
| **What story do these visuals tell?** | They show that there is a large pay disparity and that it comes from how revenue is split between players and the league. | The visuals explain that the issue is structural, not just about salary, but about how revenue is divided. | It tells a story about inequality in pay and shows that even with a new deal, the split is still not equal. |
| **Can you identify a trend that is going on here?** | The revenue split improves slightly for the WNBA over time, but still remains far from the NBA model. | There is a shift in the new CBA, but the gap between NBA and WNBA is still large. | The trend shows some progress, but not enough to reach parity. |
| **On a scale of 1–10, how easy was it to find the key data points?** | 8 – It was easy to understand overall, but small design choices made it slightly distracting at first. | 7 – Clear, but I had to take a second to fully process the court visual. | 10 – Very clear and intuitive, especially the pictograph. |
| **What are your main takeaways from these visuals?** | The disparity is significant, and the way revenue is split is the main reason why. | Even though things are improving, the system is still not equal. | The visuals clearly show why pay disparity exists and why it matters now. |
| **Is there something you wish you had more information on?** | I would like to see what happens next or how this could change in the future. | It would be helpful to see how fan engagement or revenue growth impacts these splits. | A forward-looking visual showing potential outcomes or next steps would strengthen the story. |
| **Are the sizes of text, lines, and shapes appropriate?** | Overall good, but the original font choice (Comic Sans) felt distracting and less professional. | The sizing works well, but the design could be slightly more polished. | Everything is readable and clear, especially in the basketball visual. |
| **Do the colors fit well with the story?** | The colors are clear, but I expected a stronger distinction between NBA and WNBA. | It might help to differentiate the leagues with color, but it is still understandable without it. | The consistent colors work, but adding variation could make comparisons clearer. |
| **Are the images distracting?** | The font was more distracting than the images themselves. | No, the visuals are engaging without being overwhelming. | No, the visuals are clean and easy to follow. |
| **Do you think this is an appropriate visual to showcase the information?** | Yes, especially the court and basketball visuals—they make the concept easy to grasp. | Yes, they are effective and communicate the message clearly. | Yes, these are the strongest visuals in the project. |
| **If not, would there be another graph that would help you understand this better?** | Maybe a follow-up visual showing future projections or outcomes. | A visual connecting revenue growth to player pay would help. | Something showing the impact of increased viewership on revenue splits would improve the conclusion. |
| **Can you identify what the main story or issue is?** | The main issue is pay disparity driven by unequal revenue sharing. | The story is about structural inequality in how revenue is distributed. | It highlights that the system, not just salaries, is the root of the disparity. |
| **What kind of story is it telling?** | A comparative and explanatory story about why the gap exists. | A structural story explaining how contracts shape pay. | A story about inequality and gradual progress. |
| **Does this change the way you think about the WNBA, women’s sports, or pay equity?** | Yes, it shows that the issue is more complex than just popularity. | Yes, it made me think more about how revenue structures impact fairness. | Yes, it highlights that even with growth, structural barriers still exist. |


## Identified Changes for Part III

## Identified Changes for Part III

For Part III, I made revisions across multiple visuals based on feedback from my preliminary interviews, with the most significant changes applied to Visual 1 (NCAA Boom).

For Visual 1, I split the original visual into two separate visuals that use the same base design but highlight different stories. In the first version, I focus on the crossover point where women’s NCAA viewership surpasses men’s. I added an annotation at the intersection and increased the size of the star marker to make that moment more visible and easier to interpret. In the second version, I focus on the historical gap in viewership. I used arrows and annotations between the two lines to draw attention to the difference over time while maintaining the larger star for consistency.

Beyond Visual 1, I also incorporated feedback into my other visuals. For the split court (Visual 5), I addressed concerns about the original font choice, as Comic Sans was seen as distracting and unprofessional. While there was also feedback suggesting using different colors to distinguish between the NBA and WNBA, I chose not to implement this change. The visuals are designed to be viewed consecutively, and maintaining a consistent color scheme reinforces that the comparison is based on the same measure—revenue split—rather than shifting attention to league branding.

Additionally, feedback highlighted that the court and basketball pictograph (Visual 4) were the most intuitive and engaging visuals. These effectively translated abstract financial differences into something more tangible and easy to understand. However, some viewers noted that the more traditional charts, while clear and digestible, did not carry the same level of creativity. This reflects a tradeoff between clarity and creativity that I intentionally balanced across the project.

Finally, a key gap identified across interviews was the lack of a forward-looking conclusion. While the visuals clearly establish the catalyst (growth in viewership), the issue (pay disparity), and the structural cause (revenue splits), they do not yet address what comes next. Based on this feedback, a potential next step would be to introduce a concluding visual that shows how increases in public engagement and revenue could influence future revenue splits or player compensation.

## Research Synthesis

| Research synthesis | Anticipated changes for Part III |
|------------------------------------------|---------------------------------------------------------------------------------|
| Viewers found the background image visually appealing but distracting from the data. | Simplify or remove the background image so the focus remains on the data rather than decorative elements. |
| Viewers were confused because the visual was telling multiple stories at once (crossover vs. historical gap). | Split the original visual into two separate visuals, each focused on a single story. |
| The crossover point where women’s viewership surpasses men’s was not immediately clear. | Emphasize the intersection by increasing the size of the marker and adding a clear annotation. |
| The historical gap between men’s and women’s viewership was not clearly highlighted. | Add arrows and annotations between the lines to explicitly show and explain the gap over time. |
| Viewers needed clearer guidance on what to focus on. | Use stronger annotations and visual cues to direct attention to the key takeaway in each version. |
| The split court visual was engaging but the font choice felt distracting and unprofessional. | Replace Comic Sans with a more neutral, professional font while maintaining the visual concept. |
| Some viewers suggested using different colors for NBA vs. WNBA comparisons. | Maintain a consistent color scheme to reinforce that the comparison is based on the same metric (revenue split) and avoid unnecessary distraction. |
| The court and basketball visuals were the most intuitive and memorable. | Preserve these designs as core visuals and use them as anchors for audience engagement. |
| More traditional charts were clear but lacked the same level of creativity. | Maintain clarity in these visuals while considering subtle design improvements for consistency across the project. |
| The visuals clearly explain the “why now” and the issue of pay disparity, but lack a forward-looking conclusion. | Develop an additional visual that explores future implications, such as how increased revenue or fan engagement could impact revenue splits or player compensation. |

> **Final thoughts:** The biggest takeaway from these interviews was that clarity matters more than complexity, but engagement also plays a critical role. My original visual attempted to show too much at once, which made it harder to interpret. Moving forward, I prioritized separating ideas into distinct visuals while maintaining a cohesive narrative. At the same time, I recognized the importance of balancing clarity with creativity and ensuring that the project not only explains the issue, but also points toward its broader implications.

## Research Synthesis

| Research synthesis | Anticipated changes for Part III |
|------------------------------------------|---------------------------------------------------------------------------------|
| Viewers found the background image visually appealing but distracting from the data. | Simplify or remove the background image so the focus stays on the data rather than decorative elements. |
| Viewers were confused because the visual was telling multiple stories at once (crossover vs. historical gap). | Split the original visual into two separate visuals, each focused on a single story. |
| The crossover point where women’s viewership surpasses men’s was not immediately clear. | Emphasize the intersection by increasing the size of the marker and adding a clear annotation. |
| The historical gap between men’s and women’s viewership was not clearly highlighted. | Add arrows and annotations between the lines to explicitly show and explain the gap over time. |
| Viewers needed clearer guidance on what to focus on. | Use stronger annotations and visual cues to direct attention to the key takeaway in each version. |

> Final thoughts: The biggest takeaway from these interviews was that clarity matters more than complexity. My original visual tried to show too much at once, which made it harder to interpret. I will take this advice forward as I start to compile my other visuals together. 

## References
_List any references you used here._

## AI acknowledgements
Chatgpt was used for proper formatting on github and grammatical errors in text. 

