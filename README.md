# Row Health Marketing Insights
## The goal of this project is to investigate the performance of marketing campaigns at Row Health in order to surface recommendations on marketing budget allocation across future campaign categories.

Founded in 2016, Row Health is a medical insurance company serving over thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. 

The budget is allocated to drive two primary objectives: 1) **to increase the number of customer signups**, and 2) **to raise awareness of Row Health’s brand across the country**.

## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

<img width="812" height="554" alt="311928824-c51a152c-796c-4e64-82b4-db3141a88e0c-2" src="https://github.com/user-attachments/assets/03c616eb-047e-440c-a555-0c20fc08d0ee" />

## Insights Summary
In order to evaluate campaign performance, we focused on the following key metrics:

- **Signup Rate**: The percent of people who see a campaign and subsequently sign up for a Row Health plan.
- **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.
- **Click through Rate**: The percent of people who see a campaign and click on the associated link.
- **Cost per Click**: The average dollars spent in order to acquire a click from each campaign link.

### Signup Rate
- Across 12 campaign categories, Health For All campaign performed 4X better than the second best campaign in terms of signup rate (2.08%) and signed up the second most customers (3.5K).
- The high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate (2.78%) of all the campaign’s three types.
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.27%.


### Cost per Signup
- Coverage Matters campaign was the most efficient campaign, having the lowest CPS while producing the #2 signup rate, completely due to the Product Promotion campaign type.
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($178), compared to an average of $3.70, as well as the lowest number of signups (23).
- Two COVID-based campaigns also had abnormally high CACs at $2.2K and $1.2K as well as one Health Awareness campaign at $940/customer.

### Click through Rate
- The top two campaign categories by CTR, Health For All and Benefit Updates, were each driven by a single stand out campaign type (Health Awareness at 37% and Policy Information at 31%). These same two campaign types ranked #1 and #2 in CTR across all 12 categories.
- Every campaign outperformed Health For All in impressions, but its CTR was nearly 4X that of Tailored Health Plans (25% vs 7%), the impression leader.
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

### Cost per Click
- CPC only showed meaningful statistical insight at the campaign type level, and the data clearly points to consolidating budget toward Health Awareness and Policy Information while reducing investment in high CPC types that aren't delivering proportional returns on either clicks or reach.
- Social and referral acquisition channels accounted for 92% of all sign-ups and had the lowest cost per click and highest volume of impressions and clicks.

## Recommendations
- Redirect the budget of Golden Years Security and Insure Your Health, the worst performing campaign categories when looking at all North Star metrics, towards any of the top performing campaigns (Health For All, Coverage Matters, Compare Health Coverage, Healthy Living). Those four campaigns performed above average in multiple North Star metrics, making them perfect candidates for increased budget.

- Each campaign category runs too many campaign types simultaneously, diluting budget across underperforming types. The data is clear on which types drive signups, Health Awareness for Health For All ($0.69 CPS), Product Promotion for Coverage Matters ($0.30), Policy Information for Healthy Living ($0.92 CPS), and Customer Testimonial for Compare Health Coverage ($1.80 CPS). The remaining types within these categories cost anywhere from $25-$2,239 per signup for a fraction of the results. Narrow each category to its top 1-2 performing campaign types and reallocate the rest of the budget there.

- The COVID Awareness campaign type should be renamed and refreshed quarterly to reflect trending health topics (e.g. Cyclosporiasis in Q3 2026), keeping content timely and relevant to potential customer’s concerns.

- Reduce budget for email and direct acquisition channels and redirect towards social, referral and marketplace. 

## Dashboard
The dashboard can be found in Tableau Public here. This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.
