<img src="images/Massachusetts_CaseStudy.png?raw=true"/>

## Massachusetts Education System Analysis

### Why Massachusetts Schools?

My mom was a teacher at a grade school in Pennsylvania for most of my life. I grew up with an inside view of teaching.

I knew that education was a field I was interested in and used to dream of working at a large school. Teaching was not for me and I try to take any chance I get to work with educational data.

I've wanted to live in Boston for some time now and being able to analyze data from the Massachusetts school system is an exciting opportunity.

Exploring this dataset and creating visualizations has provided me with informative insights into the educational system and the state of schools in Massachusetts. It's made me wonder what the status is for other education systems across the United States.

### What the Data Says

The Massachusetts school system is made up of hundreds of schools in multiple districts. Each one with its own student ratings and data. 

Success for this project is decided by the following:
<ul>
  <li>A report on the state of the school system</li>
  <li>How does class size affect college admission?</li>
  <li>What are the top math schools in the state?</li>
  <li>What schools are struggling the most?</li>
</ul>

The analysis concluded with the following insights:
<ul>
  <li><strong>Springfield District</strong> has <strong>3 public schools</strong> in the bottom 10</li>
  <li>The top math schools are all <strong>public schools</strong></li>
  <li><strong>Larger class sizes</strong> mean more students <strong>go to college</strong> after graduating</li>
  <li>Schools with <strong>more disadvantaged students</strong> have <strong>less students and lower graduation and college rates</strong> while schools with <strong>more advantaged students</strong> have <strong>more students and higher graduation and college rates</strong></li>
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

The bottom 10 schools include <strong>three from Springfield District</strong>. All three are public schools with a <strong>graduation rate ranging from 16.7% to 8.7%</strong>. Springfield District consists of 10 schools; four have a graduation rate under 50%, the other 6 have a rating over 50%. Springfield High School is 5th in the bottom 10 schools and 88% of its students are economically disadvantaged and only 11.6% go on to college.

<img src="images/MA_Bottom10.png?raw=true"/>

The three public schools in Springfield District are:
<ul>
  <li>Gateway to College at Springfield Technical Community College: <strong>16.7% graduation rate</strong></li>
  <li>Springfield High School: <strong>11.6% graduation rate</strong> and <strong>88% rate</strong> of economically disadvantaged students</li>
  <li>Springfield Public Day High School: <strong>8.7% graduation rate</strong></li>
</ul>

With <strong>three schools in the bottom 10</strong>, another under 50% graduation rate, and the other six over 50%, Springfield District has several warning signs that it needs extra support and funding.

### Best Math Schools

The top 10 math schools are made up of <strong>10 districts</strong>, containing <strong>8 schools</strong>, all of which are <strong>public schools</strong>. Each school has a graduation rate of <strong>over 90%</strong> and the rate of students disadvantaged is <strong>below 19%</strong>. 

<img src="images/MA_Top10Passing.png?raw=true"/>

These signs all point to the students doing well academically and financially. The policies and decisions that support these districts should be evaluated for key strategies that result in the high ratings.

### Onward to College

College determines success in this society. When a high school doesn't set up its students for college, their chance of financial independence, quality of life, and thriving goes  down. In Massachusetts, there are several schools that show the <strong>correlation between class sizes and going to college</strong>. Two of these schools are:
<ul>
  <li>Fecteau-Leary Junior/Senior High School</li>
  <li>Boston Preparatory Charter Public High School</li>
</ul>

<img src="images/MA_CollegeVsClass.png?raw=true"/>

These schools are one the opposite ends of the correlation range. <strong>Fecteau-Leary Junior/Senior High School</strong> is a public school in the Lynn District. Fecteau-Leary Junior/Senior High School has no passing rate for 4th grade math and <strong>52.3% of its students struggle economically</strong>. It has a <strong>class size of 12 students</strong> and <strong>32% of its students graduate</strong> with <strong>10.5% going to college</strong>.

<strong>Boston Preparatory Charter Public High School</strong> is a charter school in the Boston Preparatory Charter Public District. Boston Preparatory Charter Public High School has no passing rate for 4th grade math and <strong>39% of the students are economically disadvantaged</strong>. It has a <strong>class size of 34 students</strong> and <strong>75% of its students graduate</strong> with <strong>95.2% going to college</strong>.

Students have a better chance of going to college if the quality of the education received in high school support their endeavors to continue with higher education. Quality education is supported by several factors. This analysis shows that <strong>larger class sizes lead to more students attending college</strong>. This may be because students can support each other or students flock to schools with better ratings or the students who have an advantage economically are more likely to go to a school that better supports their students and then on to college.

### Massachusetts School System

The state of Massachusetts School System has districts that are distinctly disadvantaged students and districts of advantaged students. Most of the funding and support goes to the schools of advantaged students. This results in higher graduation rates, higher numbers of students going to college, and more students. 

The two schools that show the opposing extremes of the spectrum are:
<ul>
  <li>Groton Dunstable Regional</li>
  <li>Springfield High School</li>
</ul>

<img src="images/MA_best_worst.png?raw=true"/>

<strong>Groton Dunstable Regional</strong> is a public school with <strong>846 students</strong>, <strong>3.1% of which are disadvantaged</strong>. Its <strong>class size is 17 students</strong> with <strong>98.2% graduating</strong> and <strong>89.7% going to college</strong>.

<strong>Springfield High School</strong> is a public school with <strong>101 students</strong>, <strong>88% are disadvantaged</strong>. Its <strong>class size is 7 students</strong> with <strong>11.6% graduating</strong> and <strong>58.8% going to college</strong>.

<img src="images/MA_best_worst_college.png?raw=true"/>

Groton Dunstable Regional has impressive ratings and almost all of their graduates go to college. It is a good school for students who have intentions of higher education. Springfield High School has more disadvantaged students, less students, and a lower college rate. This school shows signs of needing more funding and support to better prepare more students for college as well as providing more resources to assist those looking to attend and go on to college.

### Key Insights for School/Education System

The following educational insights for Massachusetts School System are advised to increase their ratings and student numbers:
<ul>
  <li><strong>The bottom 10 schools</strong> and the districts they are in should receive more support, funding, and teaching incentives to improve the school, its teachers, and the quality of education</li>
  <li><strong>Scholarships and fully funded education</strong> should be offered to students who are disadvantaged to give them a good education and a better chance at college</li>
  <li>The <strong>policies and decisions</strong> that support districts with higher ratings should be evaluated and applied to other school districts</li>
  <li>Schools with <strong>larger class sizes</strong> have more students going to college after graduating</li>
</ul>

To conclude, Massachusetts bottom 10 schools contain <strong>3 public schools from Springfield district</strong>. Also <strong>public schools are the top math schools</strong> in the state. In Massachusetts, <strong>bigger class sizes</strong> results in <strong>more students going to college</strong>. In opposition to this correlation, <strong>more disadvantaged students mean less students and lower rates</strong> while <strong>less disadvantaged students mean more students and higher rates</strong>.

In addition, educational insights are provided to increase students and ratings. <strong>Schools with more disadvantaged students</strong> should be given <strong>more support to improve</strong>.

Thanks for reading! If you have any questions, please email me at the email below. Also, I am looking for a <strong>full-time remote job as a data analyst</strong>, so if you have any recommendations, please message me on [LinkedIn](https://www.linkedin.com/in/xaviertquinn/) or email me at xaviertquinn@gmail.com. Any information would be very helpful!
