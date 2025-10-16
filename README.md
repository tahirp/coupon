# Coupon Acceptance Analysis

## Project Summary

This project explores a dataset from a survey on Amazon Mechanical Turk to understand the factors that influence whether a driver accepts a coupon delivered to their cell phone. The dataset includes user attributes (like age, gender, income, and frequency of visiting various establishments), contextual attributes (destination, weather, time, passenger), and coupon attributes (type, expiration).

The primary goal of this analysis is to distinguish between customers who accepted a driving coupon versus those that did not, focusing specifically on different coupon types to identify key influencing factors.

## Key Findings

The analysis focused on understanding the factors influencing the acceptance of different coupon types. Key findings include:

*   **Overall Acceptance:** The overall proportion of coupons accepted across all types is approximately 57%.
*   **Coupon Type Influence:** The acceptance rate varies significantly by coupon type. For example, Restaurant (<$20) coupons have a noticeably higher acceptance rate (~71%) compared to Bar coupons (~41%).
*   **Influential Factors (Restaurant <$20 Coupons):** A detailed investigation into Restaurant (<$20) coupons revealed several factors influencing acceptance:
    *   **Destination:** 'No Urgent Place' destinations are associated with higher acceptance.
    *   **Passenger:** Having a 'Friend' or 'Partner' as a passenger increases acceptance.
    *   **Weather & Time:** 'Sunny' weather and specific times of day ('2PM', '6PM') show higher acceptance rates.
    *   **Expiration:** Coupons with a longer expiration ('1d') are more likely to be accepted.
    *   **Demographics:** Younger age groups (21-30) and certain middle-income brackets tend to have higher acceptance.
    *   **Frequency of Visits:** Counterintuitively, moderate to frequent visitors of similarly priced restaurants show higher acceptance.
    *   **Proximity & Direction:** Closer coupon locations and those in the 'Opposite Direction' of the destination have higher acceptance.
*   **Feature Interactions:** Combinations of factors are also important. For instance, having a 'Friend' or 'Partner' as a passenger *in Sunny weather* particularly increases the likelihood of accepting a Restaurant (<$20) coupon. Younger age groups also show very high acceptance rates at specific times ('2PM', '6PM').

*   **Influential Factors (Bar Coupons):** An initial exploration of Bar coupons indicated that factors like frequency of visiting bars and age significantly influence acceptance, with more frequent bar visitors and older individuals (over 25 when combined with frequency) showing higher acceptance rates compared to other groups. The combination of frequent bar visits, adult passengers, and certain occupations also showed a higher acceptance rate.

## Actionable Items & Recommendations

Based on the findings, businesses can improve coupon acceptance rates by:

*   **Targeting based on Context:** Delivering coupons when the user has 'No Urgent Place' as a destination, is with friends or a partner, and when the weather is sunny.
*   **Considering Timing & Expiration:** Leveraging peak times like 2 PM and 6 PM for delivery and offering coupons with longer expiration periods.
*   **Demographic Targeting:** Focusing marketing efforts on younger demographics and specific income brackets for certain coupon types.
*   **Leveraging Proximity:** Prioritizing coupon delivery when the business is close, even if it's in the opposite direction.
*   **Exploring Interactions:** Using the identified feature interactions to create more specific and effective targeting segments (e.g., targeting younger people with friends at 2 PM on a sunny day for a restaurant coupon).

## Link to Jupyter Notebook

You can find the detailed analysis and code in the following Jupyter notebook:

[Link to your Jupyter Notebook here]

---
