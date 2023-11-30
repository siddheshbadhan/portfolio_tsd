| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Storyboard
https://preview.shorthand.com/cQrTqtVilB3vkviG

# User research 

## Goal of the Research
To evaluate and refine real estate market trend visualizations, ensuring they effectively meet the informational and usability needs of property investors, buyers, and market enthusiasts and researchers.

## Target audience

The protocol focuses on:
Property Investors: Individuals or entities actively investing in real estate.
Property Buyers: Individuals in the process of or planning to buy property.
Real Estate Market Enthusiasts: People with a keen interest in real estate trends but not professionally involved.
Real Estate Researchers: Academics or professionals conducting research in real estate markets. 

## Approach to Identifying Representative Individuals:

To find a diverse and representative sample, the following methods will be employed:
Investment Groups and Forums: Engage with online real estate investment communities and local investment groups.
Real Estate Buying Platforms and Forums: Target users on platforms dedicated to property buying and selling.
Educational Institutions and Research Centers: Reach out to universities and research centers focusing on real estate studies.
Social Media and Online Communities: Utilize targeted social media campaigns and online communities interested in real estate.

## Interview script
- **Introduction:** Brief the purpose of the interview and ensure confidentiality.
- **Background Questions:**
1. Can you describe your experience or interest in real estate investment or buying?
2. How frequently do you rely on market trend data and visualizations?
- **Visualization Assessment:**
1. What are your first thoughts on these visualizations?
2. Which elements do you find most and least effective?
3. How clear and understandable are the data and trends?
4. What additional data or features would you find useful?
- **Specific Feedback:**
1. For each type of visualization (line graphs, heat maps, etc.), what are your thoughts regarding their clarity and usefulness for your purposes?
2. How well do these visualizations meet your specific needs or expectations?
- **Closing:** Express gratitude for their time and offer to share updates on the project. 

## Interview findings
### Interviewee 1: Property Investor, 40s
1. **Key Insights:**
- The line graph showing price per square foot over time was deemed useful, but the investor suggested adding a filter for property types.
- They found the spike in the first graph curious and suggested a tooltip to explain such anomalies.
- The heat map was a favorite due to its clear representation of price distributions.
2. **Key Quote:**
"I need to see trends for specific types of properties, not just broad categories."

### Interviewee 2: Property Buyer, 30s
1. **Key Insights:**
- They found the bar chart comparing borough prices to be straightforward but suggested adding a median price line for context.
- They were confused by the building age graph; the large spikes were misleading and needed clarification.
- They appreciated the sales volume graph but suggested it be correlated with price trends on the same timeline.
2. **Key Quote:**
"I want to know if the months with higher sales volumes also have higher prices."

### Interviewee 3: Real Estate Researcher, 50s
1. **Key Insights:**
- They were intrigued by the historical data but pointed out that the 'null' category in the 'Building Age' graph could distort interpretations.
- They suggested that the comparative analysis lacks depth without considering property sizes.
- For the zip code map, they recommended integrating demographic data for a richer analysis.
2. **Key Quote:**
"Without size normalization, the borough comparison doesn't tell the whole story."


# Analysis of Feedback
## Consistent Feedback Across Interviews:
- **Desire for Detailed Context:** All interviewees expressed a need for additional context within the visualizations. This includes explanations for anomalies and better historical data contextualization.
- **Interest in Specific Segmentation:** Both the property investor and buyer wanted the ability to drill down into specific data relevant to their interests, such as property types or price ranges.
- **Data Normalization:** There was a common suggestion that comparing average prices across boroughs would be more meaningful if normalized by property size.

## Conflicting Observations:
- **Use of Heat Maps:** The property investor appreciated the heat map for its clear representation, while the researcher suggested that without demographic data, it might not be fully useful.
- **Building Age Data:** The buyer found the spikes in the building age graph misleading, whereas the researcher found them intriguing but pointed out issues with the 'null' values.

## Planned Changes Based on Feedback:
1. **Enhanced Contextual Information:** Interactive elements like tooltips will be added to explain data spikes and anomalies.
2. **Segmentation and Filtering:** Introduce filters for property types, and possibly for different price ranges, to allow users to tailor the information to their specific needs.
3. **Normalization of Data:** Modify the comparative analysis to include property size, ensuring the data comparison is more equitable.
4. **Correlation of Data Points:** Overlay sales volume trends with price trends to investigate possible correlations, addressing the buyer's interest in the relationship between sales volume and pricing.
5. **Demographic Data Integration:** For the zip code-level map, add demographic data layers to provide insights into the socio-economic factors that might affect market dynamics.

## Improvements in Part III:
Planned Changes to Visualizations

1. **Line Graph:**
- Introduce property type filters to allow users to view trends for residential, commercial, or industrial properties separately.
- Implement interactive tooltips to explain significant data points or anomalies.

2. **Building Age Graph:**
- Clarify what the spikes represent and address the 'null' category.
- Introduce a median value line for better trend visualization.

3. **Comparative Analysis Bar Chart:**
- Add median price lines to give a benchmark for comparison.
- Normalize the data by property size to offer more meaningful comparisons.

4. **Sales Volume Graph:**
- Overlay or juxtapose with price trends to allow for comparative analysis over the same time frame.

5. **Zip Code-Level Map:**
- Consider adding layers or filters to display demographic data, which can be toggled on and off for a more comprehensive analysis.
