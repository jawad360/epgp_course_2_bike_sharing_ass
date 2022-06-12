# Bike Sharing Assignment
> Investigating the Rental Bike Demand for the company BoomBikes.


## Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
The model has p-value and VIF within acceptable range of < 0.05 and < 5 respectively
**F(cnt) = 0.2353 * yr - 0.0969 * holiday + 0.6612 * temp + 0.0224 * spring + 0.0893 * summer + 0.1564 * winter - 0.2901 * light+precipitation - 0.0710 * misty_cloudy - 0.0415 * july + 0.0999 * sept**
- Temperature contribute highly positive to count, every unit increase in temperature contributes to 0.66 increase in count
- Holiday has negative contribution, meaning ppl must be using the bikes for offices or school
- If its cloudy or light rain, it contributes negatively, meaning ppl will not prefer bikes
- Year as positive contribution, meaning the coming years will have more count than previous

Created by [@jawad360] - feel free to contact me!