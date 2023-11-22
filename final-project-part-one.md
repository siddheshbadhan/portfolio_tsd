| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Part I: Final Project

# Project Outline - Navigating NYC Real Estate: Insights for Success

# High Level Summary
This project delves into the intricacies of New York City's real estate market through a comprehensive analysis of property sales data. It aims to unravel the myriad factors influencing property values and sales trends, from geographical nuances to building characteristics. Designed to resonate with real estate professionals, prospective buyers, renters, and market analysts, the narrative offers a multifaceted perspective on how different elements converge to shape the dynamics of one of the world's most vibrant real estate markets. The project not only sheds light on current market conditions but also provides a lens through which future trends and opportunities can be discerned, making it an invaluable resource for anyone navigating the complex terrain of NYC real estate.
 
# Detailed Project Structure
1. Project Introduction
Objective: To provide deep insights into the New York City real estate market using interactive data visualizations.
Scope: Analysis of NYC property sales data, covering various dimensions like price, location, and building characteristics.
Target Audience: Real estate agents, brokers, prospective homebuyers, renters, and market analysts.
2. Data Overview
Source: NYC Property Sales Records.
Contents: Borough, Neighborhood, Building Class, Tax Class, Block, Lot, Easement, Building Class at Present, Address, Zip Code, Residential Units, Commercial Units, Total Units, Land Square Feet, Gross Square Feet, Year Built, Building Class at Time of Sale, Sales Price, Sale Date, $0 Sales Price.
Preprocessing Needs: Data cleaning, categorization of building classes, normalization of sales prices, and calculation of price per square foot.
3. Visualization Principles
Simplicity and Clarity: Ensuring that each visualization is straightforward and communicates the intended message clearly.
Storytelling with Data: Creating a narrative that logically connects various data points, providing a comprehensive view of the NYC real estate market.
Audience-Centric Design: Tailoring visualizations to the specific needs and interests of the target audience, making the data relatable and actionable.
4. Data Analysis and Visualization
Market Trends and Price Analysis: Line graphs and area charts depicting price trends and comparisons across neighborhoods and boroughs.
Building Class and Age Analysis: Scatter plots and bubble charts to explore the relationship between building age, type, and sales price.
Sales Volume Trends: Bar charts and line graphs showing sales volume changes over time, highlighting seasonal patterns.
Geographic Distribution: Heat maps and geographic visualizations to compare property prices and characteristics across different areas of the city.
5. Insights and Interpretation
Identifying Key Market Dynamics: Such as the impact of location, building age, and type on property prices.
Comparative Analysis: Across different boroughs, neighborhoods, and property types to uncover unique market characteristics.
6. Designing the Final Presentation
Layout and Flow: Structuring visualizations in a sequence that guides the audience through different aspects of the NYC real estate market.
Narrative Development: Crafting a story that connects individual visualizations into a cohesive narrative.
Aesthetic Consideration: Maintaining consistency in design elements to enhance readability and engagement.
7. Conclusion and Call to Action
Summary of Findings: A concise recapitulation of the most significant insights derived from the analysis.
Recommendations: Actionable suggestions for different stakeholders based on data-driven insights.
Call to Action: Encouraging real estate professionals to integrate these insights into their strategies, and guiding potential buyers/renters in making informed decisions.


## Initial sketches

![image](https://github.com/siddheshbadhan/portfolio_tsd/assets/57594239/2ccce69f-31a9-41ed-802c-501ce4580f24)

![image](https://github.com/siddheshbadhan/portfolio_tsd/assets/57594239/24e9798c-5fdc-462f-8394-8bd8b0524d77)


# The data
The dataset revolves around property sales data in New York City. It's a comprehensive collection of information that details various aspects of property transactions, including location, building characteristics, and sale specifics. This dataset is an invaluable resource for analyzing real estate trends and dynamics within New York City. It has close to 2.5 lakh rows and covers the data from 2017-2019.

Columns in the Dataset
- Borough: Identifies the NYC borough where the property is located.
- Neighborhood: Designated by the Department of Finance, representing the common neighborhood names.
- Building Class Category: Broad categorization of properties (e.g., residential, commercial) for easy identification of similar property types.
- Tax Class at Present: Classification of properties into one of four tax classes, based on use.
- Block: A subdivision of the borough indicating the property's location.
- Lot: Further subdivision of a Tax Block, representing a property's unique location.
- Easement: Rights for limited use of the property by another entity.
- Building Class at Present: Detailed classification describing a property's current use and construction style.
- Address: Street address of the property.
- Zip Code: Postal code of the property.
- Residential Units: Number of residential units in the property.
- Commercial Units: Number of commercial units in the property.
- Total Units: Total number of units in the property.
- Land Square Feet: Land area of the property in square feet.
- Gross Square Feet: Total area of all building floors measured from the exterior surfaces.
- Year Built: Year when the property structure was built.
- Building Class at Time of Sale: Classification describing the property's use or construction style at the time of sale.
- Sales Price: Transaction value of the property.
- Sale Date: Date when the property was sold.
- $0 Sales Price: Indicates non-monetary transactions.

I am also using Building class dataset (https://www.nyc.gov/assets/finance/jump/hlpbldgcode.html) to map the building code with the description. The join operation is being performed in Tableau. The original dataset requires lots of cleaning and merging of dataset since the dataset is available for each separate borough year wise, so for all 5 boroughs and for the 3 years from 2017-2019, it needs to be merged and combined to a single file. This data is publicly available and can be used for various analyses and insights generation.

Link: https://www.nyc.gov/site/finance/taxes/property-annualized-sales-update.page 

# Method and medium

The final project will be presented as an interactive digital narrative, utilizing a platform such as Tableau Public or a similar web-based storytelling tool. The focus will be on unraveling the complexities of the New York City real estate market, targeting real estate professionals, prospective homebuyers, renters, and market analysts. The story will:
- Engage through Interactive Visualizations: Leveraging the power of Tableau, the project will feature dynamic graphs, heat maps, and scatter plots. This approach allows users to explore data in an interactive manner, drilling down into specifics like neighborhoods, property types, and price ranges.
- Narrative Structure: The project will craft a compelling narrative about the NYC real estate market, underpinned by robust data visualizations. It will guide the audience through various aspects of the market, from broader trends to detailed analysis of specific neighborhoods or property types.
