                                                   ![](https://media.giphy.com/media/3o6Zt2RqEvIEwn452w/giphy.gif)

# Health_Insurance_Cross_Sell_Prediction
Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else.

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

**id** : Unique ID for the customer

**Gender** : Gender of the customer

**Age** : Age of the customer

**Driving_License** 0 : Customer does not have DL, 1 : Customer already has DL

**Region_Code** : Unique code for the region of the customer

**Previously_Insured** : 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

**Vehicle_Age** : Age of the Vehicle

**Vehicle_Damage** :1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

**Annual_Premium** : The amount customer needs to pay as premium in the year

**PolicySalesChannel** : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

**Vintage** : Number of Days, Customer has been associated with the company

**Response** : 1 : Customer is interested, 0 : Customer is not interested

### As we can improve KNN Classifier Model more using more hyper parameter tuning which can give us more desired results which will be more helpful.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Conclusions :

We can observe from our Initial analysis from distribution of our features and outlier detection and whole EDA analysis we can conclude that:
Customers who have never had a vehicle damaged are only 0.5 percent interested in vehicle insurance.
Vehicles less than one year old are more likely to have insurance, with 66 percent of those insured, and vehicles older than one year but less than two years old are 33 percent insured.

## All Model Interpretation and conclusion:

From Here also we can Conclude that KNN Classifier will be our best model to use for this whole problem statment so that Insuarance Companies can easily get the proper idea about the customers they have to target and how to target so that they can retain most of the customers and generate higher revenue.

## Future Work Suggestions:

Insurance Comapnies should promot and provide more customer friendly insuarance.
Benefits for clients with vehicles older than two years.
And for analysis there should be more parameters for the analysis more some more features will help the analysis to be more explainatory.
