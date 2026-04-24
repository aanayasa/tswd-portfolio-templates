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

## User Feedback Table

| Questions | Interview Feedback |
|----------|-------------------|
| **At a glance, what is the first thing you notice about this visual? (Visual 1)** | This is a cool visual with the arena background, but my attention immediately goes to the image rather than the data being shown. |
| **What is this visual about? (Visual 2)** | This visual is about viewership growth in the WNBA, and it was very intuitive to understand. |
| **Evaluate ability to identify trends and key data (Visual 3)** | I like the use of basketballs to depict salary. At a glance, I focus more on the number of balls rather than the actual dollar amounts. It is clear that men make more, but I then have to look more closely to understand what each ball represents in terms of dollars. |
| **Can you define a trend that’s going on here? (Visuals 1 & 2)** | In Visual 1, women’s NCAA viewership is steadily increasing, with a large spike around 2024. Visual 2 shows a similar trend but does a better job highlighting how dramatic the increase is between 2022 and 2024. |
| **On a scale of 1–10, how easy was it to find the key data points?** | Visual 1: 10<br>Visual 4: 7<br>Visual 6: 8 |
| **What are your main takeaways from this visual? (Court visual / Visual 5)** | This is a strong visual because it focuses on revenue split rather than dollar amounts. It is a more dramatic and engaging way to show the disparity and leaves a lasting impression on the viewer. |
| **Is there something on here you wish you had more information on?** | I wish there was more explanation for why the revenue split is so drastically different compared to the NBA. |
| **Are the sizes of text, lines, and shapes appropriate?** | The original court visual used Comic Sans, which felt distracting and less professional. |
| **Do the colors fit well with the story?** | I like that the visuals use blue and orange, which feel consistent with the NBA theme. |
| **Are the images distracting?** | The arena background in the first visuals is slightly distracting, even though it is visually appealing. It raises the question of what the background is meant to represent. |
| **What kind of story is it telling?** | The visuals follow a strong narrative flow. They start with the NCAA and Caitlin Clark as a catalyst, then show how that momentum carries into the WNBA, followed by the pay disparity, and finally explain the structural issue through the CBA and revenue split. |
| **Does this change the way you think about the WNBA, women’s sports, or pay equity?** | Yes, it makes me more interested in supporting women’s sports. As someone with little prior knowledge, I previously thought the issue was about matching NBA salaries despite lower popularity. Now I understand that the real issue is about how revenue is shared, not just the total amount. |


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
| The court and basketball visuals were the most intuitive and memorable. | Preserve these designs as core visuals and use them as anchors for audience engagement. |
| More traditional charts were clear but lacked the same level of creativity. | Maintain clarity in these visuals while considering subtle design improvements for consistency across the project. |

> **Final thoughts:** The biggest takeaway from these interviews was that clarity matters more than complexity, but engagement also plays a critical role. My original visual attempted to show too much at once, which made it harder to interpret. Moving forward, I prioritized separating ideas into distinct visuals while maintaining a cohesive narrative. At the same time, I recognized the importance of balancing clarity with creativity and ensuring that the project not only explains the issue, but also points toward its broader implications.


## References
_List any references you used here._

## AI acknowledgements
Chatgpt was used for proper formatting on github and grammatical errors in text. 

