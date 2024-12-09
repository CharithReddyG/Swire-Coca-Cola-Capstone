# MSBA CAPSTONE - SWIRE COCA-COLA PREDICTIVE MODELING

## Business problem and Project Objective

Swire Coca-Cola, one of the largest Coca-Cola bottlers in the U.S., faces significant operational challenges due to unplanned machine downtimes across its six production plants, which annually produce approximately 192 million cases of beverages. Mechanical limitations, premature wear and tear, and unforeseen breakdowns result in only 94.4% of the required orders being fulfilled, leading to an estimated $60 million in annual losses. 

The inefficiency stems from a reactive maintenance strategy, where machines are repaired only after the failure, causing prolonged inactivity and increased costs. To bridge the output gap and reduce losses, Swire Coca-Cola needs a solid understanding of downtime patterns, their influence on productivity, and actionable insights for deploying maintenance solutions.

This project addresses the persistent problem of unplanned machine downtime at Swire Coca-Cola by using historical maintenance data to provide actionable insights and shift to a proactive maintenance approach. The project aims to improve equipment dependability and streamline production efficiency by analyzing failure trends and downtime records. 

The key objectives include:
* Analyzing downtime trends and identifying high-cost functional nodes across six Swire Coca-Cola production plants.
* Pinpointing critical equipment and parts most susceptible to failure.
* Evaluating the impact of preventive maintenance on reducing downtime and operational disruptions.
* Delivering strategic recommendations to boost productivity, minimize costs, and enhance profitability.

## Our solution to the Business Problem

Our team analyzed historical maintenance records from the Internal Warehouse Controller (IWC) system, focusing on identifying patterns in breakdowns, high-cost areas, and equipment reliability issues. We developed predictive maintenance models using advanced analytical techniques to anticipate potential failures and recommend timely interventions.

We began by examining downtime data across six production plants, identifying critical trends, and mapping them to specific functional nodes and equipment types. For instance, Monza and Cota Production emerged as high-risk plants, with frequent downtimes and median survival times of 1,386 and 1,143 days, respectively. These downtimes significantly contributed to overall production losses. Using Kaplan-Meier survival analysis, we quantified the survival times for various equipment types, such as fillers and packers, uncovering that components like Packer 1 had a notably short survival time of 176 days. Cox proportional hazards modeling clarified the risk factors and their influence on equipment failures, allowing us to pinpoint critical failure points and the associated financial impact. 

In addition to understanding the factors contributing to downtime, we conducted simulations of "what-if" scenarios to evaluate the potential impact of implementing preventive maintenance before median survival times. These simulations revealed that proactive strategic maintenance planning could significantly reduce unplanned events. For instance, by targeting maintenance interventions at 80% of the median survival time for high-risk equipment, we observed a 20-30% reduction in unplanned maintenance events, leading to a corresponding decrease in downtime hours. 

The results were synthesized into actionable recommendations, emphasizing the importance of stocking critical spare parts, prioritizing high-risk equipment, and optimizing maintenance schedules. This proactive approach minimizes production losses and enhances operational reliability, ensuring critical equipment remains functional during peak demand. By addressing failures before they occur, Swire Coca-Cola can improve productivity and maintain a more consistent production output across its six plants.

## My Contribution to the project

As a critical contributor to this project, my role encompassed a range of analytical and exploratory tasks that significantly advanced the insights and outcomes of our work. I handled missing values to ensure data quality and reliability, particularly suggesting an identical approach for imputing missing values in variables like "Equipment Valid From Date."  Through univariate analysis, I provided insights into breakdown trends over the years and maintenance activity types through compelling visualizations. In bivariate analysis, I explored the relationships between various factors and downtime trends in production line efficiency, particularly within Functional Area Nodes 4 and 5. I extended this to a multivariate analysis, examining downtime trends across different plants and maintenance activities while performing rigorous outlier detection to ensure data integrity.

I categorized breakdowns by equipment type through feature engineering, identifying Fillers and Packers as the primary contributors to downtime. I investigated equipment failure patterns comprehensively, focusing on the intervals between breakdowns to design data-driven maintenance strategies. I analyzed the time to failure post-maintenance and uncovered valuable insights in optimizing maintenance schedules and enhancing operational efficiency. 

By leveraging Kaplan-Meier survival analysis, I explored time-to-failure among the equipment and identified critical maintenance intervals, providing a foundation for proactive maintenance planning. To complement this, I employed the Cox proportional hazards model to quantify risk factors influencing equipment failure probabilities, offering a robust understanding of breakdown patterns. 

Additionally, by differentiating between planned and unplanned maintenance activities, I uncovered actionable patterns that informed the implementation of proactive maintenance strategies to minimize unplanned events and associated costs. To further demonstrate the benefits of proactive maintenance, I simulated "what-if" scenarios based on 80% of median survival times, showcasing the potential for significant reductions in downtime and operational expenses. 

Beyond analysis, I drafted actionable recommendations, including prioritizing maintenance for high-risk nodes, shifting to a proactive approach, optimizing inventory for critical spare parts, and emphasizing preventive maintenance strategies. proofread and finalized our outputs to ensure clarity and precision.

## Business Value of the Solution

The solution provides Swire Coca-Cola with critical business value by addressing the challenges of unplanned downtimes and transitioning to a proactive maintenance strategy.

1. **Cost Savings**: Proactive maintenance reduces unplanned downtime, saving a significant portion of the $60 million annual losses caused by downtime.
2. **Enhanced Productivity**: Data-driven maintenance scheduling improves equipment reliability, minimizes disruptions, and helps achieve closer alignment with the production target of 192 million cases annually.
3. **Optimized Resource Utilization**: By identifying high-risk equipment and critical parts, the solution ensures the right resources are available, reducing delays and inventory costs.
4. **Strategic Inventory Management**: Insights into high-failure components enable smarter inventory strategies, ensuring availability while avoiding overstocking.
5. **Targeted Maintenance Interventions**: Prioritizing critical equipment and functional nodes ensures maintenance efforts focus on areas with the most significant impact on productivity and costs.
6. **Improved Operational Efficiency**: Addressing recurring failure patterns leads to more reliable equipment, reducing the frequency of breakdowns and operational risks.
7. **Sustainable Growth and Profitability**: By minimizing costs and improving production efficiency, the solution strengthens Swire Coca-Cola’s ability to scale operations sustainably while boosting profitability.

## Challenges/Difficulties along the way

Our team faced several challenges and limitations during the project, requiring strategic decision-making and collaborative problem-solving. One of the primary difficulties was handling the dataset’s significant missing values, particularly in key variables like maintenance plans and functional nodes. We decided against imputing missing data to preserve data integrity, which necessitated careful analysis to understand its impact. The hierarchical structure of the data, particularly across multiple functional nodes, made it challenging to distinguish planned from unplanned maintenance effectively while ensuring consistency across the dataset. Identifying and handling outliers in downtime and cost data required meticulous attention to detail to preserve the accuracy and reliability of the analysis. Implementing advanced models, such as Kaplan-Meier survival analysis and Cox proportional hazards modeling, posed another significant challenge, demanding an in-depth understanding to translate complex outputs into actionable business recommendations. Simulating "what-if" scenarios for preventive maintenance required careful definition of thresholds and assumptions to balance with practical business considerations.

The breadth of the project, including data cleaning, exploratory analysis, modeling, and drafting recommendations, had to be completed within a limited timeframe, which required prioritizing certain analyses over others. Aligning technical work with business needs and ensuring all group members were on the same page about the project's direction and goals was challenging, especially when interpreting different aspects of the data. 

## My Learnings

Working on this project has been an incredible learning experience, allowing me to delve deeply into the practical application of data analytics to solve real-world business problems. I learned how to handle large and complex datasets, focusing on cleaning and feature engineering to ensure the data's quality and relevance. By exploring advanced techniques like Kaplan-Meier survival analysis and Cox proportional hazards modeling, I understood how predictive analytics can identify patterns and inform proactive strategies. 

Most importantly, this project highlighted the importance of proactive decision-making. By simulating "what-if" scenarios, I learned how using data-driven strategies can help predict and address potential issues before they occur. This approach showed me how taking action in advance can make a big difference in improving business outcomes and solving challenges effectively. Additionally, I understood how deep learning models could be leveraged for predictive analytics. While working on this project, I explored how advanced machine-learning techniques could be applied to predict downtimes and enhance operational reliability. This highlighted the potential of incorporating deep learning techniques to achieve even more precise and reliable maintenance predictions.

Through this project, I learned the importance of presenting my work in a clear and structured way to ensure it is easily understood by a general audience. I realized that no matter how detailed the analysis or insights are, their value is lost if they are not communicated effectively. This experience taught me how to tailor my approach to make complex data and findings accessible and impactful for all stakeholders.

## Presentation Link 
[Swire Capstone Presentation](https://github.com/CharithReddyG/Swire-Coca-Cola-Capstone_Charith/blob/main/SWIRE%20PPT.pptx)

## Project File 
[Project File Link](https://github.com/CharithReddyG/Swire-Coca-Cola-Capstone_Charith/blob/main/Swire_CC_Capstone_Modeling_charith.ipynb)
