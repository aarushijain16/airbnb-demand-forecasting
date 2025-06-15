# airbnb-demand-forecasting
Unlocked the secrets of London's Airbnb market: a published study leveraging advanced machine learning and granular data insights to accurately forecast demand and pinpoint key growth drivers.

# Forecasting the London Airbnb Market 

## Executive Summary:
This project presents a comprehensive analysis of the London Airbnb Market, focusing on identifying the most critical features influencing listing prices and demand. Leveraging publicly available Airbnb data from August 2008 to March 2023, the study provides a detailed comparison of accommodation pricing between Inner and Outer London boroughs, revealing significant trends over time. Key findings demonstrate that Inner London listings command a substantial price premium, approximately 1.25 times higher than those in Outer London. 
The analysis delves into pricing variability driven by factors such as minimum nights required, 90-day availability, number of beds, bedrooms, bathrooms, and crucially, the type of room. Through segmentation by neighbourhood, the project uncovers practical, data-driven insights essential for Airbnb to refine its marketing strategis, optimise supply simulation, implement dynamic pricing models, and develop more effective policy frameworks. This work highlights actionable opportunities to enhance operational efficiency, boost host incomes, and elevate guest value within London's dynamic market. It undercovers how exploratory data analysis (EDA) can yield crucial competitive intelligence to guide strategic decision-making, with methods and findings extendable to other global cities. 

## Problem Statement:
The core objective of this project was to analyse the complex dynamics of the London Airbnb market to inform strategic decisions. Despite limitations in direct demand data for forecasting, the primary aim was to evaluate predictive modelling methods by understanding the features that significantly impact Airbnb listing and demand. The study sought to:
* Analyse the most critical features influencing Airbnb listing prices and, by extension, demand.
* Compare pricing strategies and trends between Inner and Outer London accommodation markets.
* Uncover actionable insights for Airbnb to tailor its business strategy in areas like marketing, supply management, dynamic pricing, and policy development.
* Ultimately, identify opportunities to optimise operations, enhance host incomes, and i prove guest value in London market through data-driven recommendations.

## Data Sources and Characteristics:
The analysis was conducted using a publicly available dataset of Airbnb listings for London, covering a substantial period from **August 2008 to March 2023**. 

Key features within the dataset used for analysis included:
* **Pricing-related attributes**: Influences on listing price and demand.
* **Accommodation features**: Minimum nights required to stay, availability of the accommodation in the next 90 days.
* **Property Specifics**: Number of beds, bedrooms, and bathrooms.
* **Listing Type**: The most important factor, indicating the type of room or property (e.g., entire home, private room).
* **Geographical context**: Segmentation by neighbourhood to understand localised market dynamics.

## Methodology:
A robust analytical methodology was employed, combining exploratory data analysis with advanced predictive modelling techniques:
1. **Exploratary Data Analysis (EDA)**: Extensive EDA was performed to understand data distributions, relationships between variables, and underlying market patterns. Both descriptive statistics and visualisations were utilised to extract crucial competitive insights from the AIrbnb listings data.
2. **Feature Engineering and Selection**: Key features affecting pricing variabilit were identified and analysed, including minimum nights, avaialability, number of beds, bedrooms, bathrooms, and room type.
3. **Geographical Segmentation**: Listings were segmented by neighbourhood (specifically differentiating Inner and Outer London) to provide localised insights into pricing and market behaviour.
4. **Predictive Modelling**: To evaluate their predictive capabiloties, three machine learning models were applied to predict listing prices:
   * **Decision Tree Model**
   * **Random Forest Model**
   * **Extreme Gradient Boosting (XGBoost) Model**
**Model Performance**: The **Extreme Gradient Boosting (XGBoost) Model** consistently demonstrated the most accurate and robust scores among the predictive models evaluated.

## Key Findings and Insights:
The project yielded several significant findings that offer actionable insights for Airbnb's strategic planning in London:
* **Inner London Price Premium**: Listings in Inner London command a substantial price premium, approximately **1.25 times higher** than comparable listings in Outer London boroughs. This highlights the value of central locations.
* **Key Price Drivers**: Pricing variability is significantly influenced by specific listing features, including:
  * Minimum nights required for a stay.
  * Availability of the accommodation in the next 90 days.
  * Number of beds, bedrooms, and bathrooms.
  * Most importantly, the **type of room** (e.g., entire home/apt vs. private room).
* **Actionable Business Intelligence**: The extensive exploratory data analysis successfully uncovered crucial actionable business intelligence, guiding data-driven decision-making for Airbnb.
* **Top Predictive Model**: The Extreme Gradient Boosting (XGBoost) model proved to be the most accurate and robust for predicting listing prices within the London market, providing a reliable tool for future price forecasting efforts.

## Business Impact and Recommendations:
Based on the analytical findings, several strategic recommendations are proposed for Airbnb's business strategy in London:
* **Targeted Marketing for Central Locations**: Focus marketing efforts on highlighting the prestige, convenience, and unique experiences offered by central London locations. This approach aims to attract high-value guests willing to pay the premium prices commanded by Inner London listings.
* **Transportation Partnerships**: Explore partnerships with transportation providers to create bundled travel deals or offer improved visitor access solutions to inner London listings. This could enhance guest convenience and broaden appeal.
* **Policy Engagement with Local Councils**: Collaborate with local councils to develop policies that strike a balance between housing availability and growth within the Airbnb ecosystem. More flexible and supportive regulations could stimulate supply, benefitting both hosts and guests.
* **Smart Dynamic Pricing Tools**: Develop and implement sophisticated smart pricing tools that dynamically maximise revenues across different neighbourhoods. These tools should consider demand trends, seasonality, and specific listing features to optimise pricing optimally.
* **Incentivise Outer Boroughs**: Offer pricing incentives or promotional support for listings in outer boroughs to balance demand across the city and increase income generation from these potentially underutilised regions.

By implementing these data-driven strategies, Airbnb can leverage London's unique market dynamics to boost host incomes and enhance guest value, thereby improving overall operations in this key global city. 

## Tools and Technologies:
While the specific code file is not included due to confidentiality agreements related to publication, the project extensively utilised Python for its robust statistical analysis and modelling capabilities. The primary analytical and predictive modelling tasks were performed using popular python libraries for data manipulation, exploratory data analysis, and machine learning. 

## Publication / Confidentiality Note:
This project's findings are published as Chapter 4 in the book **"Planning, Forecasting and Strategy in a Turbulent Era"**. 
**Link to Book**: 
 * **Publisher's Website**: [Planning, Forecasting and Strategy in a Turbulent Era - Edward Elgar Publishing](https://www.elgaronline.com/edcollbook/book/9781035317240/9781035317240.xml#:~:text=Forecasting%2C%20Planning%20and%20Strategy%20in%20a%20Turbulent%20Era%20emphasizes%20the,perform%20well%20under%20immense%20pressure.)
 * **Amazon**: [Planning, Forecasting and Strategy in a Turbulent Era - Edward Elgar Publishing](https://www.amazon.in/Forecasting-Planning-Strategy-Turbulent-Era/dp/1035317230)

Due to the terms of the publishing and copyright agreement, the original dataset and the complete project code files cannot be publicly shared within this repository. This README.md provides a comprehensive overview of the project's objectives, detailed methodology, significant findings, and actionable business insights. 

## Limitations and Future Work**:
The study acknowledges certain limitations, primarily related to **demand data  limitations**, which influenced the analytical approach towards evaluating predictive modelling methods for pricing. 

For future work, the methodologies ad findings from this London-focused study **could be extended and adapted to other major cities worldwide**, providing broader applicability and insights into diverse Airbnb markets. Further research could also explore additional external factors or morw granular demand metrics if suitable data becomes available. 

## Visualisations:
* **Figure 1**: [Inner vs. Outer London Pricing Comparison]()
* **Figure 2**: 
