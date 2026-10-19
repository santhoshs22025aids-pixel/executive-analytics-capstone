# Executive Analytics Capstone — Customer Churn

## Decision question
Which customer groups should a fictional subscription team contact first to reduce avoidable churn?

## Scope and five insights
- Dataset: supplied synthetic customer sample; 15 records.
- Observed churn: 7 of 15 customers (46.7%); observed retention: 53.3%.
- Churned customers account for ₹409.93 in summed monthly charges; this is an exposure proxy, not a forecast.
- Highest observed contract churn: Month-to-Month (100.0%; n=7).
- Highest observed tenure-band churn: 0-12 months (100.0%; n=6).
- Highest observed support-ticket-band churn: 4+ tickets (100.0%; n=5).

## Recommendation
Run a measured service-outreach pilot for month-to-month customers with several recent support tickets, after checking actual segment counts. Track response rate, 30/60-day retention, cost per retained customer, and feedback. Compare with a holdout or matched group before claiming impact.

## Expected impact
Treat improved retention as a hypothesis, not a guarantee. Any retained monthly-charge amount should be calculated from the customers actually retained during the pilot.

## Limitations
- Only 15 synthetic records; one customer can materially change percentages.
- No historical timeline, satisfaction score, campaign history, or intervention outcomes.
- Monthly charges associated with churned customers are an exposure proxy, not confirmed lost revenue.
- Segment associations do not establish causation; this is not a validated prediction model.
