<img src="images/Massachusetts_CaseStudy.png?raw=true"/>

## Massachusetts Education System Analysis

# REWRITE
### Why Massachusetss Schools?

My mom was a teacher at a grade school in Pennsylvania for most of my life. I grew up with an inside view of teaching.

I knew that education was a field I was interested in and used to dream of working at a big school. Teaching was not for me and I try to take any chance I get to work with educational data.

I've had a goal to live in Boston and being able to analyze data from the Massachusetts school system is an exciting opportunity.

Exploring this dataset and creating visualizations has provided me with informative insights into the educational system and the state of schools in Massachusetts. It's made me wonder what the status is for other education systems across the United States.

### What the Data Says

The Masschusetts school system is made up of hundreds of schools in multiple districts. Each one with its own student rating and graduation percentage. The data provides the following insights:

<ul>
  <li>
    x<strong>LIST DATA INSIGHTS</strong>
  </li>
  <li>
    x<strong>x</strong>
  </li>
  <li>
    x<strong>x</strong>
  </li>
  <li>
    x<strong>x</strong>
  </li>
</ul>

REWRITE

### Data background 

This <a href=URL>dataset</a> is 

It contains:

<ul>
  <li><strong>NUMBER rows</strong> of ROWS</li>
  <li><strong>NUMBER columns</strong> of COLUMNS</li>
</ul>

Each row contains information for one school. For instance 2-3 COLUMNS.

Those columns include:

<ul>
  <li>
    LIST SOME OF THE COLUMNS USED
  </li>
  <li>
    x
  </li>
  <li>
    x
  </li>
  <li>
    x
  </li>
  <li>
    x
  </li>
</ul>



REWRITE

### TITLE FOR INSIGHT 1

REWRITE
---


I find myself wondering what the age range is for most apps I use. For some, it's easier to hypothesize based on trends. For others, like DoorDash, it's harder to infer. In these circumstances, I find a query into the data creates clearer results.

It was fairly easy to find the oldest and youngest DoorDash customers. Using a MAX and MIN aggregate function on the age column, I was able to determine that the age of DoorDash customers range from <strong>24 years old to 80 years old</strong>. 

<img src="images/DoorDash_CustomerAge.png?raw=true"/>

In addition, I created an IF function that categorizes each customers' age into a group. This allowed me to answer the question of what age group makes up most of the customer base. As shown below, <strong>ages 36-50 make up 42%</strong> of the customer base, followed by <strong>ages 51-65 at 34%</strong>.

### TITLE FOR INSIGHT 2

REWRITE
---


The total spent on DoorDash orders was <strong>$1.2 million</strong>. With an <strong>R squared value of 0.67</strong>, 67% of the change in amount spent can be explained by a change in income.

There are two outliers. One has a low income and a high spend value. The other has a high income and a low spend value. These might be accounted for by an error in data collection. Alternatively, the former outlier could be explained by a customer with a low income taking advantage of deals that lower order fees. The latter outlier could be explained by a customer with a high income who only orders from DoorDash once a week for certain meetings. Or a college student using their parents account.

<img src="images/DoorDash_Scatter.png?raw=true"/>

Using an IF function, I categorized the time since last order value into groups of 1 week, 1 month, 2 months, 3 months, and 4 months. Using these last order groups, I calculated the total spent in each category using the SUM aggregate function. 

<img src="images/DoorDash_TotalSpent_LastOrder.png?raw=true"/>

The most spent was 3 months ago, with a total of <strong>$380,536</strong>. A campaign or reduction of fees might account for this increase in the total spent. The least amount spent, at <strong>$102,241</strong> was in the 1 week category. This might be accounted for by the smaller category size. 1 week vs 1 month is a big difference in time. However, at 1 month, the total spent was <strong>$292,622</strong>. A difference of $63,475 between 1 month and <strong>$356,097</strong> at 2 months is still a significant change. Again, this might be accounted for by a campaign or deal on the app, or that month might have had a big holiday or school event, such as finals week.

### TITLE FOR INSIGHT 3

REWRITE
---


Finding the average amount spent was pretty simple. The AVERAGE aggregate function calculated <strong>$562.76</strong> as the average. <strong>40%</strong> of customers spent over the average amount. The other <strong>60%</strong> spent under the average amount. 

<img src="images/DoorDash_OverUnder_AverageSpent.png?raw=true"/>

The age group that spent the most was customers who are <strong>66 years old and above</strong>, followed by those <strong>51-65 years old</strong>. This might be explained by customers getting a promotion and increase in salary or reaching retirement age. Likewise, it could be inferred that those who are older order more because of health problems that prevent them from cooking regularly.

<img src="images/DoorDash_AgeAverageSpent.png?raw=true"/>

### TITLE FOR INSIGHT 4

REWRITE
---


Using an AVERAGE aggregate function, the average customer use of DoorDash was calculated to be <strong>6.88 years</strong>. This is supported by the above graph showing the average spent by age group. Each group is at least 6 years and the amount spent continuously increases since 36 years of age. 

<strong>1,108 customers</strong> have used DoorDash longer than the average, while <strong>1,097 customers</strong> have used DoorDash less than the average amount of time. 

<img src="images/DoorDash_OverUnder_AverageUse.png?raw=true"/>

The age group with the most customers over the average use time is <strong>36-50 years old</strong>. This age group also have the most customers under the average use time. This means most of the customers in that age group started using DoorDash when they were <strong>24-35 years of age</strong>.

<img src="images/DoorDash_OverUnder_AverageUse_AgeGroup.png?raw=true"/>

### Key Insights for School/Education System

Educational insights for Massachusetts School System to increase their ratings.

<ul>
  <li>
    x<strong>LIST INSIGHTS FOR EDUCATIONAL IMPROVEMENT</strong>
  </li>
  <li>
    x<strong>x</strong>
  </li>
  <li>
    x<strong>x</strong>
  </li>
  <li>
    x<strong>x</strong>
  </li>
</ul>

REPEAT DATA INSIGHTS FROM BEGINNING OF ARTICLE

To reiterate, DoorDash has a large variety of customers. Age ranges from <strong>24 years old to 80 years old</strong>. Customers spent <strong>$562.76 on average</strong>, resulting in a <strong>total of $1.2 million</strong>, being spent on food delivery. The average time a customer used the app was <strong>6.88 years</strong>.

REPEAT EDUCATIONAL INSIGHTS

In addition, marketing insights are provided to increase DoorDash customers and company revenue. Certain <strong>age groups should be targeted</strong> through specific advertising campaigns.

REPEAT BELOW PARAGRAPH WITH OTHER WORDS WHEN POSSIBLE

Thanks for reading! If you have any questions, please email me at the email below. Also, I am looking for a <strong>full-time job as a data analyst</strong>, so if you have any recommendations, please message me on LinkedIn, <a href="https://www.linkedin.com/in/xaviertquinn/">Xavier Quinn</a>, or email me at xaviertquinn@gmail.com. Any information would be very helpful!
