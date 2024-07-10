<img src="images/solar system.png?raw=true"/>

## Analysis of Planetary Satellites

### Why space?

When I was growing up, my family lived in rural areas where I could see the stars and planets at night. I loved it so much, I got a telescope for my birthday.

I still love looking at the stars. 

Exploring the entities in space was a fun project to work on. It reignited my love of learning about space.

### What's interesting about these satellites?

There is a several insights found from the data.

<ul>
  <li>There are <strong>16 satellites</strong> recorded, <strong>5 of which belong to Saturn</strong></li>
  <li>The satellite with the highest mass is<strong>Ganymede at 148.2</strong>, while the satellite with the lowest mass is <strong>Tethys at 0.6173</strong></li>
  
    
  <li>The customer use average is <strong>6.88 years</strong></li>
</ul> 

### Data background

This [dataset](http://en.wikipedia.org/wiki/List_of_Solar_System_objects_by_size) was used as part of a Data Analytics course. 

It contains:
<ul>
  <li><strong>35 rows</strong> of solar system entities (customers and their information)</li>
  <li><strong>12 columns</strong> of attributes for entities in the solar system</li>
</ul>

One row shows information for an entity, such as volume, mass, and density.

The columns include:
<ul>
  <li><strong>body</strong> - the name of the satellite</li>
  <li><strong>volume</strong> - the volume of the satellite measured in cubic kilometers</li>
  <li><strong>mass</strong> - the mass of the satellite measured in kilograms</li>
  <li><strong>density</strong> - the density of the satellite measured in gram per cubic centimetre</li>
  <li><strong>surface_gravity</strong> - the standard gravity measurement of the satellite</li>
</ul>

### Planet satellites

x

number of satellites
<img src="images/carbon 5 ss.png?raw=true" width="200"/>

<img src="images/5 ss.png?raw=true" width="200"/>

satellites to planets
<img src="images/carbon 7 ss.png?raw=true" width="200"/>

<img src="images/7 ss.png?raw=true" width="200"/>



The total spent on DoorDash orders was <strong>$1.2 million</strong>. With an <strong>R squared value of 0.67</strong>, 67% of the change in amount spent can be explained by a change in income.

There are two outliers. One has a low income and a high spend value. The other has a high income and a low spend value. These might be accounted for by an error in data collection. Alternatively, the former outlier could be explained by a customer with a low income taking advantage of deals that lower order fees. The latter outlier could be explained by a customer with a high income who only orders from DoorDash once a week for certain meetings. Or a college student using their parents account.


Using an IF function, I categorized the time since last order value into groups of 1 week, 1 month, 2 months, 3 months, and 4 months. Using these last order groups, I calculated the total spent in each category using the SUM aggregate function. 


The most spent was 3 months ago, with a total of <strong>$380,536</strong>. A campaign or reduction of fees might account for this increase in the total spent. The least amount spent, at <strong>$102,241</strong> was in the 1 week category. This might be accounted for by the smaller category size. 1 week vs 1 month is a big difference in time. However, at 1 month, the total spent was <strong>$292,622</strong>. A difference of $63,475 between 1 month and <strong>$356,097</strong> at 2 months is still a significant change. Again, this might be accounted for by a campaign or deal on the app, or that month might have had a big holiday or school event, such as finals week.

### Examining mass

x

max
<img src="images/carbon 1 ss.png?raw=true" width="200"/>

<img src="images/1 ss.png?raw=true" width="200"/>

min
<img src="images/carbon 2 ss.png?raw=true" width="200"/>

<img src="images/2 ss.png?raw=true" width="200"/>

avg
<img src="images/carbon 3 ss.png?raw=true" width="200"/>

<img src="images/3 ss.png?raw=true" width="200"/>




I find myself wondering what the age range is for most apps I use. For some, it's easier to hypothesize based on trends. For others, like DoorDash, it's harder to infer. In these circumstances, I find a query into the data creates clearer results.

It was fairly easy to find the oldest and youngest DoorDash customers. Using a MAX and MIN aggregate function on the age column, I was able to determine that the age of DoorDash customers range from <strong>24 years old to 80 years old</strong>. 


In addition, I created an IF function that categorizes each customers' age into a group. This allowed me to answer the question of what age group makes up most of the customer base. As shown below, <strong>ages 36-50 make up 42%</strong> of the customer base, followed by <strong>ages 51-65 at 34%</strong>.



### Examination of the satellites

The Planetary mass classification organizes planets and satellites by their mass. The categories are:

<ul></ul>
  <li>Hyper-Jupiter: mass over 4131.8</li>
  <li>Super-Jupiter: mass between 635.6 and 4131.8</li>
  <li>Mid-Jupiter: mass between 158.9 and 635.6</li>
  <li>Sub-Jupiter: mass between 31.8 and 158.9</li>
  <li>Midplanet: mass between 10 an 31.8</li>
  <li>Super-Earth: mass between 2 and 10</li>
  <li>Mid-Earth: mass between 0.5 and 2</li>
  <li>Sub-Earth: mass below 0.5</li>
</ul>

Using SQL, I created two CASE inquiries that categorized the satellites by this classification.

The first inquiry classified each satellite into its prospective size category.

<img src="images/carbon 13 ss.png?raw=true" width="200"/>

<img src="images/13 ss.png?raw=true" width="200"/>

The next inquiry looked at the number of planets and satellites that fell into each category.

<img src="images/carbon 12 ss.png?raw=true" width="200"/>

<strong>Mid-Earth</strong> had the most satellite classifications with <strong>10 satellites</strong>, followed closely by <strong>Hyper-Jupiter at 7 satellites</strong> and <strong>Sub-Jupiter at 6</strong>.

<img src="images/12 ss.png?raw=true" width="200"/>

### Key insights into planetary satellites

x


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
