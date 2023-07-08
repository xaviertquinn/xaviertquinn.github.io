<img src="images/Massachusetts_CaseStudy.png?raw=true"/>

## Massachusetts Education System Analysis

### Why Massachusetss Schools?

My mom was a teacher at a grade school in Pennsylvania for most of my life. I grew up with an inside view of teaching.

I knew that education was a field I was interested in and used to dream of working at a large school. Teaching was not for me and I try to take any chance I get to work with educational data.

I've wanted to live in Boston for some time now and being able to analyze data from the Massachusetts school system is an exciting opportunity.

Exploring this dataset and creating visualizations has provided me with informative insights into the educational system and the state of schools in Massachusetts. It's made me wonder what the status is for other education systems across the United States.

### What the Data Says

The Masschusetts school system is made up of hundreds of schools in multiple districts. Each one with its own student ratings and data. 

Success for this project is decided by the following:
<ul>
  <li>A report on the state of the school system</li>
  <li>How does class size affect college admission?</li>
  <li>What are the top math schools in the state?</li>
  <li>What schools are struggling the most?</li>
</ul>

The analysis concluded in the following insights:

<ul>
  <li><strong>Springfield District</strong> has <strong>3 public schools</strong> in the bottom 10</li>
  <li>The top 10 schools are <strong>50% public schools</strong> and <strong>50% charter schools</strong></li>
  <li><strong>Hingham High</strong>, part of <strong>Hingham District</strong> has a <strong>91% math passing rate</strong></li>
  <li><strong>89.7%</strong> of<strong>Groton Dunstable Regional</strong>'s student <strong>go to college</strong> while only <strong>58.8%</strong> of <strong>Springfield High School</strong> goes to college</li>
</ul>

### Data background 

This [dataset](https://www.kaggle.com/datasets/ndalziel/massachusetts-public-schools-data) shows many ratings and details from hundreds of school in Massachusetts.

It contains:

<ul>
  <li><strong>1,861 rows</strong> of schools, their geographic information, and educational ratings</li>
  <li><strong>298 columns</strong> of information for each school recorded</li>
</ul>

Each row contains information for one school. For instance school name, total enrollment, and average class size.

Those columns include:

<ul>
  <li>School Name</li>
  <li>School Type</li>
  <li>% Economically Disadvantaged</li>
  <li>% MCAS_4thGrade_Math_P+A</li>
  <li>TOTAL_Enrollment</li>
</ul>

### Bottom 10 Schools

The bottom 10 schools include three from Springfield District. All three are public schools with a graduation rate ranging from 16.7% to 8.7%. Springfield District consists of 10 schools; four have a graduation rate under 50%, the other 6 have a rating over 50%. Springfield High School is 5th in the bottom 10 schools and 88% of its students are economically disadvantaged and only 11.6% go on to college.

<img src="images/MA_Bottom10.png?raw=true"/>

The three public schools fron Springfield District are:
<ul>
  <li>Gateway to College at Springfield Technical Community College: <strong>16.7% graduation rate</strong></li>
  <li>Springfield High School: <strong>11.6% graduation rate</strong> and <strong>88% rate</strong> of economically disadvantaged students</li>
  <li>Springfield Public Day High School: <strong>8.7% graduation rate</strong></li>
</ul>

With <strong>three schools in the bottom 10</strong>, another under 50% graduation rate, and the other six over 50%, Springfield District has several warning signs that it needs extra support and funding.

### Best Math Schools

The top 10 schools are <strong>50% public schools</strong> and <strong>50% charter schools</strong>

REWRITE
---


The total spent on DoorDash orders was <strong>$1.2 million</strong>. With an <strong>R squared value of 0.67</strong>, 67% of the change in amount spent can be explained by a change in income.

There are two outliers. One has a low income and a high spend value. The other has a high income and a low spend value. These might be accounted for by an error in data collection. Alternatively, the former outlier could be explained by a customer with a low income taking advantage of deals that lower order fees. The latter outlier could be explained by a customer with a high income who only orders from DoorDash once a week for certain meetings. Or a college student using their parents account.

<img src="images/DoorDash_Scatter.png?raw=true"/>

Using an IF function, I categorized the time since last order value into groups of 1 week, 1 month, 2 months, 3 months, and 4 months. Using these last order groups, I calculated the total spent in each category using the SUM aggregate function. 

<img src="images/DoorDash_TotalSpent_LastOrder.png?raw=true"/>

The most spent was 3 months ago, with a total of <strong>$380,536</strong>. A campaign or reduction of fees might account for this increase in the total spent. The least amount spent, at <strong>$102,241</strong> was in the 1 week category. This might be accounted for by the smaller category size. 1 week vs 1 month is a big difference in time. However, at 1 month, the total spent was <strong>$292,622</strong>. A difference of $63,475 between 1 month and <strong>$356,097</strong> at 2 months is still a significant change. Again, this might be accounted for by a campaign or deal on the app, or that month might have had a big holiday or school event, such as finals week.

### Onwardto College

switch with insight 4

<strong>Hingham High</strong>, part of <strong>Hingham District</strong> has a <strong>91% math passing rate</strong>

REWRITE

    Hingham High, public school
    6.4% of students are economically disadvantaged
    1,199 students
    99.3% of students graduate
    Hingham district has a 91% passing rate for 4th Grade math
    
---


Finding the average amount spent was pretty simple. The AVERAGE aggregate function calculated <strong>$562.76</strong> as the average. <strong>40%</strong> of customers spent over the average amount. The other <strong>60%</strong> spent under the average amount. 

<img src="images/DoorDash_OverUnder_AverageSpent.png?raw=true"/>

The age group that spent the most was customers who are <strong>66 years old and above</strong>, followed by those <strong>51-65 years old</strong>. This might be explained by customers getting a promotion and increase in salary or reaching retirement age. Likewise, it could be inferred that those who are older order more because of health problems that prevent them from cooking regularly.

<img src="images/DoorDash_AgeAverageSpent.png?raw=true"/>

### Massachusetts School System

<strong>89.7%</strong> of<strong>Groton Dunstable Regional</strong>'s student <strong>go to college</strong> while only <strong>58.8%</strong> of <strong>Springfield High School</strong> goes to college

Springfield District shows sign it needs an increase in funding and support

    Groton Dunstable Regional, public school
    Groton-Dustable district
    846 students
    class size of 17 students
    3.1% economically disadvantaged students
    89.7% go to college
    

    Springfield High School, public school
    Springfield district
    101 students
    class size of 7 students
    88% economically disadvantaged students
    58.8% go to college

    
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
<ul>
  <li><strong>Springfield District</strong> has <strong>3 public schools</strong> in the bottom 10</li>
  <li>The top 10 schools are <strong>50% public schools</strong> and <strong>50% charter schools</strong></li>
  <li><strong>Hingham High</strong>, part of <strong>Hingham District</strong> has a <strong>91% math passing rate</strong></li>
  <li><strong>89.7%</strong> of<strong>Groton Dunstable Regional</strong>'s student <strong>go to college</strong> while only <strong>58.8%</strong> of <strong>Springfield High School</strong> goes to college</li>
</ul>

To reiterate, DoorDash has a large variety of customers. Age ranges from <strong>24 years old to 80 years old</strong>. Customers spent <strong>$562.76 on average</strong>, resulting in a <strong>total of $1.2 million</strong>, being spent on food delivery. The average time a customer used the app was <strong>6.88 years</strong>.

REPEAT EDUCATIONAL INSIGHTS

In addition, marketing insights are provided to increase DoorDash customers and company revenue. Certain <strong>age groups should be targeted</strong> through specific advertising campaigns.

REPEAT BELOW PARAGRAPH WITH OTHER WORDS WHEN POSSIBLE

Thanks for reading! If you have any questions, please email me at the email below. Also, I am looking for a <strong>full-time job as a data analyst</strong>, so if you have any recommendations, please message me on LinkedIn, <a href="https://www.linkedin.com/in/xaviertquinn/">Xavier Quinn</a>, or email me at xaviertquinn@gmail.com. Any information would be very helpful!
