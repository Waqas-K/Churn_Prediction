<img src = https://d57439wlqx3vo.cloudfront.net/iblock/fba/fba0a0a157413b1ee9bc04edd9e7861a/2298095e630c7748c6f6e009e027ee06.png
     />
    
<font size=3>
<br/>
    
---
    
**What Is Churn Rate?**<br/>
The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop doing business with an entity. It is most commonly expressed as the percentage of service subscribers who discontinue their subscriptions within a given time period. It is also the rate at which employees leave their jobs within a certain period. For a company to expand its clientele, its growth rate (measured by the number of new customers) must exceed its churn rate.
    
**Telecommunications Industry Churn Rates**<br/>
The churn rate is a particularly useful measurement in the telecommunications industry. This includes cable or satellite television providers, Internet providers, and telephone service providers (landline and wireless service providers).

As most customers have multiple options from which to choose, the churn rate helps a company determine how it is measuring up to its competitors. If one out of every 20 subscribers to a high-speed Internet service terminated their subscriptions within a year, the annual churn rate for that Internet provider would be 5%.

   
**Customer Churn Prediction**<br/>
Telecom companies often have customer service branches which attempt to win back defecting clients, because recovered long-term customers can be worth much more to a company than newly recruited clients. The focus is on voluntary churn, because it typically occurs due to factors of the company-customer relationship which companies control, such as how billing interactions are handled or how after-sales help is provided.
    
Predictive analytics use churn prediction models that predict customer churn by assessing their propensity of risk to churn. Since these models generate a small prioritized list of potential defectors, they are effective at focusing customer retention marketing programs on the subset of the customer base who are most vulnerable to churn.

<font color='green'>**In this project we will use the Orange Telecom's Churn Dataset to predict customer churn which would help the company develop focused retention programs.**</font>
    
---

**Metric We Will Use**<br/>
 Now let’s consider precision and recall as they relate to churn.

Definitions:
 - **Precision:** Of all the users that the algorithm predicts will churn, how many of them do actually churn?
 - **Recall:** What percentage of users that end up churning does the algorithm successfully find?

**_Example of Precision_:**
Consider a re-engagement email campaign which says something like “We noticed you may be leaving us. Please don’t!” You’d likely want to ensure that the precision for this email was high. In other words, you would want to minimize the number of happy users who see this email, and instead have this email almost exclusively hit users in danger of churning.

**_Example of Recall_:**
On the other hand, consider an email that you want to send more broadly to your user base – maybe an offer to receive $5 of the next purchase. You’d be less concerned with users who are not in danger of churning receiving this marketing message. Ideally, though, you would want anyone who might churn to see the email. In this case, you would want your recall to be higher than your precision.

As you can see, both precision and recall are important for evaluating the performance of a churn prediction algorithm, so we will be using **F1-Score**