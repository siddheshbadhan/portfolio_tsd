# Biggest Tomato & Potato producers

## Selection of the Dataset
"I selected this dataset because it offers an extensive global production data of tomatoes and potatoes over 50 years. This vast timespan and geographical scope present an opportunity for in-depth insights. Initially, the analysis focused solely on tomato production, missing out on crucial country-specific production details. This gap highlighted the dataset's potential for a more nuanced analysis, sparking my interest in exploring it further."

Link: https://data.world/makeovermonday/2023w17

## Original Visualization and Critique
"The original visualization showcased the world's top 12 tomato producers in a specific year between 1961 and 2021. It featured a bar chart and a pie chart, displaying production values and country names, embellished with national flags and color-coded for clarity.

What Stood Out: The vibrant color scheme and clear country listings were immediately eye-catching.
Effective Aspects: The bar chart effectively ranked countries by tomato production volume.
Limitations: The donut chart's overlay on a busy background image detracted from data clarity, and the redundancy of both bar and donut charts for the same data was unnecessary.
Final Thoughts: My redesign aims to represent data on a global map, showing total production in tonnes per country. I plan to simplify the color palette to shades of a single color, indicating production volume, and eliminate the bar chart to avoid redundancy. Additionally, I will present production values in aggregated thousands or millions for clarity."


## Initial Sketch and User Feedback

<div class='tableauPlaceholder' id='viz1700093712254' style='position: relative'><noscript><a href='#'><img alt='Tomato&#47;Potato Production across the globe ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment4_1_17000934654180&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment4_1_17000934654180&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment4_1_17000934654180&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1700093712254');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
<br>
"In my initial Tableau sketch, I visualized the data on a global map, aggregating it into millions for clarity and changing the color palette. I included filters for year and item type and revised the title and legend.

User Feedback: Generally, the map-based presentation and data aggregation were well-received. Viewers appreciated the specific data filters.
Suggested Improvements: Despite the comprehensive dataset on the map, feedback suggested highlighting the top 10 producing countries for simplicity. I also received advice on adjusting the color palette for color blindness considerations and moving production values to tooltips for aesthetic purposes."

## Final Design and Reflection

<div class='tableauPlaceholder' id='viz1700097662957' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;R3&#47;R3W3BXCNF&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;R3W3BXCNF' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;R3&#47;R3W3BXCNF&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1700097662957');                   
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { 
    vizElement.style.width='1000px';
    vizElement.style.height='827px';
  } else if ( divElement.offsetWidth > 500 ) { 
    vizElement.style.width='1000px';
    vizElement.style.height='827px';
  } else { vizElement.style.width='100%';
          vizElement.style.height='877px';
         }                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                        
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

<br>
"In response to feedback, I refined the color palette to a single hue and shifted production figures to tooltips. The final dashboard consists of two sections: a global map displaying production data and a list of the top 10 producing countries. I encountered challenges in accurately mapping country names, which have changed over the decades. The final title, "Global Production of Tomatoes & Potatoes in Tonnes" and "Top 10 Producing Countries," better reflects the content, and the inclusion of a data source ensures proper citation. The refined design is both aesthetically pleasing and informative, successfully balancing visual appeal with data accuracy."
