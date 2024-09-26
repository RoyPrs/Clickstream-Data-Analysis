This is the clickstream data analysis for a dropshipping company. The aim is to find inactive resellers whose behavior is like activated resellers.
My approach:
- The clickstream data is oroginally in 16 tables in the database.
- In the data preparation phase, I managed to consolidate the data to have the sequence of events in each sessions for each user.
- The first analysis showed that active and inactive users have different behavior in terms of the number of sessions, event per session, and some key sessions which correlate most with intent to activation, i.e. download image/video of product.
- I fed the data to a logistice regression model that give the probability of activation for each user with 92% accracy.
- Users with 70+ percent probability were the focus of next promotions and offering to make them activate.
- With this analysis, instead of blindly working on all users base, we can focus on activating users with higher likelihood of activation.
- Also, we can segment inactive users to track their behavior and take informed approach to each segment instead of treating them as a whole.
