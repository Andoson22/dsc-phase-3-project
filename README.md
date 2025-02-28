
## Project Description

For this project, we're investigating the SyriaTel telecommunications company churn data, and deciding which factors are the most "important" to identifying potential churns before they happen to maximize our profitability.

### The Data

The data used comes from one source:

SyriaTel Telecommunications Company Churn Data
This data is found in the Data folder

### Key Findings

What Leads Customers To Stop Using The Service?

Why Do Customers Continue To Use The Service?

These questions can help the company maximize their efficiency in saving money, and are looked at in determining the best ways to prevent customer churn and promote customer retention.  A cornerstone business concept that holds true for almost any market is that it's much cheaper to keep current customers than to gain new ones.  This mantra allows us to maximize our efficiency when looking to spend money on customer retention, and allows us to not waste too much time or money trying to identify people who are likely to stay.

![image](https://raw.githubusercontent.com/Andoson22/Customer-Churn-Data/main/Images/Ratio%20of%20Churn.png)

Here we can see that our data has a minority imbalance, which makes sense because if we were losing a significant portion of the customers each period, there wouldn't be any services left to provide to people.

Our most important features were total day minutes, total day charge, total eve minutes, total eve charge, total night minutes, total night charge.  Below we can see a pairplot of our features.

![image](https://raw.githubusercontent.com/Andoson22/Customer-Churn-Data/main/Images/Features%20Pairplot.png)

#### Recommendations
1. Possibly offer an unlimited minutes plan to current customers as well as advertise it to potential ones.  This could help with both customer retention AND customer gain in the marketplace.
2. Improve customer service.  As the number of customer service calls increased so did the percentage of churns within the sample size.
3. Potentially drop international plan if not super profitable.

## Conclusion

The following made up the most important features that a customers likelihood to churn:

Total Day Minutes/Total Day Charge-  These two features were the most important, which seems reasonable given their observable and intuitive linear relationship.

Total Eve Minutes/Total Eve Charge-  Again, these two features seem reasonable given their observable and intuitive linear relationship.

Total Night Minutes/Total Night Charge-  Again, these two features seem reasonable given their observable and intuitive linear relationship.

International Plan- A high proportion of international plan users, churn.  Look into dropping international plan option, or realizing it's a reality of the feature.

Customer Service Calls- Can we limit number of service calls by improving customer service, or its it mostly related to the telecommunications service itself and the number of calls to customer service is just a byproduct.


#### Future Work

Would like to investigate the international plan more thoroughly to see if there are any patterns that can be identified and prevented.  Possibly could be due to individuals moving from country to country, so they sign up initially but then after moving they drop the plan because it's no longer needed.  Maybe look to drop international plans altogether if the cost/profit ratio isn't stacking up to the others.

Another thing I'd like to look into is the customer service center.  I think it would be interesting to see if the service itself is all to blame for the increasing churn with increasing calls.  If we can limit the # of calls customers make to customer service by providing more exceptional service while on the first few calls, we may be able to limit the number of customer who churn.  Maybe not a complete overhaul to the system, but a few improvements here and there could go a long way to helping retain customers that have trouble with the service.

