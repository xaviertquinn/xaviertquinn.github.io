<img src="images/analyzing music.png?raw=true"/>

## Analyzing Music: Artists' and Their Tracks

### Why music?

When I was a kid, music became a huge part of my life by offering an escape. 

I spent a portion of my childhood learning violin and started to slowly teach myself how to play guitar in 2022.

I've studied how music is made in my personal time. Learning how my favorite songs were created made them even better.

So I jumped at the chance to explore data on musical artists. 

### What's interesting about artists and their music?

genres and playlists
rock n roll 90s music

Brazil had the highest number of sales at 21??

employees
peacock - brazil at 21



There is a wide range of customer insights from the data found online.

<ul>
  <li>The oldest customer is <strong>80 years old</strong>, while the youngest customer is <strong>24 yeas old</strong></li>
  <li>The total spent was <strong>$1,240,896.00</strong></li>
  <li>The average spent was <strong>$562.76</strong></li>
  <li>The customer use average is <strong>6.88 years</strong></li>
</ul> 

### Data background

x



This [dataset](https://github.com/nailson/ifood-data-business-analyst-test/blob/master/ifood_df.csv) is modified from the interview process for iFood, Brazil's DoorDash equivalent.

It contains:

<ul>
  <li><strong>2,205 rows</strong> of customers and their information</li>
  <li><strong>36 columns</strong> of customer attributes</li>
</ul>

Each row contains information for one customer. For instance income, age, and date joined.

Those columns include:

<ul>
  <li>Income: Customer's Yearly Income</li>
  <li>MntTotal: Total Amount Spent by Customer</li>
  <li>Kidhome: Number of Young Kids in Home</li>
  <li>Teenhome: Number of Teenagers in Home</li>
  <li>Recency: Number of Days Since Last Purchase</li>
  <li>AcceptedCmp6: Did The Customer Accept Offer in 6th Campaign</li>
  <li>Age: Age of Customer</li>
  <li>Customer_Days: How Many Days Has Customer Been a Customer</li>
  <li>DateJoined: The date the customer first became a customer</li>
</ul>

### Examining x
Age Demographics

x

I find myself wondering what the age range is for most apps I use. For some, it's easier to hypothesize based on trends. For others, like DoorDash, it's harder to infer. In these circumstances, I find a query into the data creates clearer results.

It was fairly easy to find the oldest and youngest DoorDash customers. Using a MAX and MIN aggregate function on the age column, I was able to determine that the age of DoorDash customers range from <strong>24 years old to 80 years old</strong>. 

<img src="images/DoorDash_CustomerAge.png?raw=true"/>

In addition, I created an IF function that categorizes each customers' age into a group. This allowed me to answer the question of what age group makes up most of the customer base. As shown below, <strong>ages 36-50 make up 42%</strong> of the customer base, followed by <strong>ages 51-65 at 34%</strong>.

### Analysis of Influencing Factors on Total Spent

The total spent on DoorDash orders was <strong>$1.2 million</strong>. With an <strong>R squared value of 0.67</strong>, 67% of the change in amount spent can be explained by a change in income.

There are two outliers. One has a low income and a high spend value. The other has a high income and a low spend value. These might be accounted for by an error in data collection. Alternatively, the former outlier could be explained by a customer with a low income taking advantage of deals that lower order fees. The latter outlier could be explained by a customer with a high income who only orders from DoorDash once a week for certain meetings. Or a college student using their parents account.

<img src="images/DoorDash_Scatter.png?raw=true"/>

Using an IF function, I categorized the time since last order value into groups of 1 week, 1 month, 2 months, 3 months, and 4 months. Using these last order groups, I calculated the total spent in each category using the SUM aggregate function. 

<img src="images/DoorDash_TotalSpent_LastOrder.png?raw=true"/>

The most spent was 3 months ago, with a total of <strong>$380,536</strong>. A campaign or reduction of fees might account for this increase in the total spent. The least amount spent, at <strong>$102,241</strong> was in the 1 week category. This might be accounted for by the smaller category size. 1 week vs 1 month is a big difference in time. However, at 1 month, the total spent was <strong>$292,622</strong>. A difference of $63,475 between 1 month and <strong>$356,097</strong> at 2 months is still a significant change. Again, this might be accounted for by a campaign or deal on the app, or that month might have had a big holiday or school event, such as finals week.

### Examination of the x
Average Spent Amount

x

Finding the average amount spent was pretty simple. The AVERAGE aggregate function calculated <strong>$562.76</strong> as the average. <strong>40%</strong> of customers spent over the average amount. The other <strong>60%</strong> spent under the average amount. 

<img src="images/DoorDash_OverUnder_AverageSpent.png?raw=true"/>

The age group that spent the most was customers who are <strong>66 years old and above</strong>, followed by those <strong>51-65 years old</strong>. This might be explained by customers getting a promotion and increase in salary or reaching retirement age. Likewise, it could be inferred that those who are older order more because of health problems that prevent them from cooking regularly.

<img src="images/DoorDash_AgeAverageSpent.png?raw=true"/>

### Exploration of x
Average Customer Use

x

Using an AVERAGE aggregate function, the average customer use of DoorDash was calculated to be <strong>6.88 years</strong>. This is supported by the above graph showing the average spent by age group. Each group is at least 6 years and the amount spent continuously increases since 36 years of age. 

<strong>1,108 customers</strong> have used DoorDash longer than the average, while <strong>1,097 customers</strong> have used DoorDash less than the average amount of time. 

<img src="images/DoorDash_OverUnder_AverageUse.png?raw=true"/>

The age group with the most customers over the average use time is <strong>36-50 years old</strong>. This age group also have the most customers under the average use time. This means most of the customers in that age group started using DoorDash when they were <strong>24-35 years of age</strong>.

<img src="images/DoorDash_OverUnder_AverageUse_AgeGroup.png?raw=true"/>

### Key Insights for x
DoorDash Marketing

x

Marketing insights for DoorDash to increase their customer base and revenue.

<ul>
  <li>Campaigns should focus on <strong>customers age 36-50 and 51-60</strong> as they are the largest age demographics in the customer base.</li>
  <li>Future campaigns should target customers who's last order was 2 months ago with the intent for them to <strong>order again before reaching 4 months</strong>.</li>
  <li><strong>Milestone deals</strong> should be implemented to reward customer use.</li>
  <li><strong>New customer advertisements</strong> should target 24-35 year olds to encourage them to start using the app.</li>
</ul>

To reiterate, DoorDash has a large variety of customers. Age ranges from <strong>24 years old to 80 years old</strong>. Customers spent <strong>$562.76 on average</strong>, resulting in a <strong>total of $1.2 million</strong>, being spent on food delivery. The average time a customer used the app was <strong>6.88 years</strong>.

In addition, marketing insights are provided to increase DoorDash customers and company revenue. Certain <strong>age groups should be targeted</strong> through specific advertising campaigns.

Thanks for reading! If you have any questions, please email me at the email below. Also, I am looking for a <strong>full-time job as a data analyst</strong>, so if you have any recommendations, please message me on [LinkedIn](https://www.linkedin.com/in/xaviertquinn/) or email me at xaviertquinn@gmail.com. Any information would be very helpful!

---

### [Next project](/)
