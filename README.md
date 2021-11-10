# Data-Science-Project-II---Price-Test
Price A/B Test


Questions Description:
A pricing experiment was conducted on a website with the main aim of increasing revenue. In the experiment, users were grouped into two groups: A (66% of the user base) and B (33% of user base). Group A users were offered a cheaper price while group B users received a higher price.

Business Questions
•	Complete an exploratory data analysis (EDA). What are your main findings looking at the data? Are there any data issues? What is your overall view into user behaviour, especially focusing on actionable insights that might increase conversion rate?

•	What is your recommendation to the company in terms of setting an optimum price for their product?

•	Can you optimize the number of days that the test is run? After how many days would you have stopped the test? Why?

Data : q2_test_results.csv
•	user_id: the Id of the user. Can be joined to user_id in user_table

•	timestamp: the date and time when the user first hit the webpage. It is in user local time 

•	source: marketing channel that led to the user coming to the site. It can be: 

•	ads-["google", "facebook", "bing", "yahoo", "other"]. That is, user coming from google ads, yahoo ads, etc. 

•	seo - ["google", "facebook", "bing", "yahoo", "other"]. That is, user coming from google search, yahoo, facebook, etc. 

•	friend_referral : user coming from a referral link of another user 

•	direct_traffic: user coming by directly typing the address of the site on the browser 

•	device: Can be mobile or web 

•	operative_system: user operative system.

•	test: (i.e. 1 -> higher price) and  (0 -> old lower price) 

•	price: the price the user sees. 

•	converted: 1 -> bought the product - 0 -> left the site without buying it. 

Data: q2_user_table.csv
Columns: 
•	user_id: the Id of the user. Can be joined to user_id in test_results table

•	city: the city where the user is located. Comes from the user ip address 

•	country: in which country the city is located 

•	lat: city latitude - should match user city 

•	long: city longitude - should match user city


