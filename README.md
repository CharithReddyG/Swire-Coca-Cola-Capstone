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

As a critical contributor to this project, my role encompassed a range of analytical and exploratory tasks that significantly advanced the insights and outcomes of our work. I handled missing values to ensure data quality and reliability, particularly suggesting an identical approach for imputing missing values in variables like "Equipment Valid From Date."  Through univariate analysis, I provided insights into breakdown trends over the years and maintenance activity types through compelling visualizations. I explored the relationships between various factors and downtime in bivariate analysis, focusing on production line efficiency, particularly within Functional Area Nodes 4 and 5. I extended this to a multivariate analysis, examining downtime trends across different plants and maintenance activities while performing rigorous outlier detection to ensure data integrity.

I investigated equipment failure patterns comprehensively, focusing on the intervals between breakdowns to design data-driven maintenance strategies. I analyzed the time to failure post-maintenance and uncovered valuable insights into optimizing maintenance schedules and enhancing operational efficiency. I categorized breakdowns by equipment type through feature engineering, identifying Fillers and Packers as the primary contributors to downtime and enabling targeted and effective interventions to reduce disruptions. By leveraging Kaplan-Meier survival analysis, I explored time-to-failure among the equipment and identified critical maintenance intervals, providing a foundation for proactive maintenance planning. To complement this, I employed the Cox proportional hazards model to quantify risk factors influencing equipment failure probabilities, offering a robust understanding of breakdown patterns. 

Additionally, by differentiating between planned and unplanned maintenance activities, I uncovered actionable patterns that informed the implementation of proactive maintenance strategies to minimize unplanned events and associated costs. To further demonstrate the benefits of proactive maintenance, I simulated "what-if" scenarios based on 80% of median survival times, showcasing the potential for significant reductions in downtime and operational expenses. 

Beyond analysis, I drafted actionable recommendations, including prioritizing maintenance for high-risk nodes, shifting to a proactive approach, optimizing inventory for critical spare parts, and emphasizing preventive maintenance strategies.


