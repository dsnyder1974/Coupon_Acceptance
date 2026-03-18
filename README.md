# Coupon Acceptance Analysis

## Overview

The goal of this project is to explore a dataset of driving scenarios
where users were offered coupons and determine what types of customers
are more likely to accept them. By analyzing customer demographics,
behavior, and contextual factors, we aim to identify patterns that
influence coupon acceptance.

## Dataset

The dataset contains observations of drivers receiving coupons while
driving and includes information about:

-   Coupon type (Bar, Restaurant, Coffee House, etc.)
-   Driver demographics (age, gender, income, marital status)
-   Passenger information
-   Contextual factors (time of day, weather, destination)
-   Behavioral patterns (frequency of visiting bars, restaurants, etc.)
-   Coupon acceptance (Y, where 1 = accepted, 0 = rejected)

Each row represents a single instance where a driver was offered a
coupon.

## Project Goals

The primary objective is to determine what characteristics are
associated with higher coupon acceptance rates. Key questions explored
include:

-   What proportion of drivers accept coupons overall?
-   Which coupon types have the highest acceptance rates?
-   Do certain demographic groups accept coupons more frequently?
-   Does past behavior (such as visiting bars or restaurants frequently)
    influence coupon acceptance?
-   How do contextual factors such as time of day or passenger type
    affect acceptance?

## Exploratory Analysis

The analysis includes:

-   Data cleaning and preprocessing
-   Handling missing values
-   Exploratory visualizations
-   Acceptance rate comparisons across different groups
-   Behavioral segmentation analysis

## Tools and Libraries

The project uses Python and several common data analysis libraries:

-   Python
-   Pandas
-   NumPy
-   Plotly
-   Seaborn / Matplotlib
-   Jupyter Notebook

## Key Findings

Analysis shows that both behavior and demographics affect coupon acceptance:

-   Visit frequency is one of the strongest predictors of acceptance. Across all coupon types, users who already engage in the behavior (e.g., dining out, going to bars, visiting coffee shops) are significantly more likely to accept coupons.
-   Convenience matters less than expected for carry-out. Distance and direction did not have as large an impact on take-away coupon acceptance, suggesting users are more flexible for this category.
-   Coupons can attract new customers in certain categories. For carry-out (and sometimes coffee), less frequent users can show high responsiveness, indicating coupons can help drive new or occasional behavior.
-   Some high-performing segments are not reliable. A few segments show very high acceptance rates but are based on small sample sizes, so those results should be interpreted with caution.

## Future Work

Possible next steps include:

-   Validate findings with additional data. Confirm that key patterns, such as the impact of visit frequency, hold across larger samples of the data.
-   Building a predictive model for coupon acceptance. Use the data to predict the likelihood of coupon acceptance, which could support more personalized and efficient targeting.

## Author

David Snyder\
Software Engineering Leader \| Data & AI Enthusiast
