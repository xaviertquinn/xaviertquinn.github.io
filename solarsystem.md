<img src="images/solar system.png?raw=true"/>

## Analysis of Planetary Satellites

### Why space?

When I was growing up, my family lived in rural areas where I could see the stars and planets at night. I loved it so much, I got a telescope for my birthday.

I still love looking at the stars. 

Exploring the entities in space was a fun project to work on. It reignited my love of learning about space.

### What's interesting about these satellites?

There is a several initial findings that can be determined just by looking at the data, which are listed below.

<ul>
  <li>There are <strong>16 satellites</strong> recorded, <strong>5 of which belong to Saturn</strong></li>
  <li>The satellite with the highest mass is<strong>Ganymede at 148.2 kilograms</strong>, while the satellite with the lowest mass is <strong>Tethys at 0.6173 kilograms</strong></li>
  <li>The classification <strong>Mid-Earth</strong> has <strong>10 planets and satellites</strong>, making it the classification with the most entities.</li>
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
  <li>body: the name of the satellite</li>
  <li>volume: the volume of the satellite measured in cubic kilometers</li>
  <li>mass: the mass of the satellite measured in kilograms</li>
  <li>density: the density of the satellite measured in gram per cubic centimetre</li>
  <li>surface_gravity: the standard gravity measurement of the satellite</li>
</ul>

### Planet satellites

The first thing I did was determine how many satellites there are by using a simple COUNT inquiry. 

<img src="images/carbon 5 ss.png?raw=true" width="400"/>

The results show there are 16 satellites.

<img src="images/5 ss.png?raw=true" width="350"/>

Looking further into it, I wrote a SQL inquiry that counted the number of satellites for each planet by listing the type_of_object before the COUNT of satellites.

<img src="images/carbon 7 ss.png?raw=true" width="400"/>

Saturn has 5 satellites, putting it at the top of the list with the highest amount. That's 31.25% of the total number of satellites. Uranus follows with 4, or 25%, and then Jupiter also at 4 satellites and 25%. Pluto, Neptune, and Earth follows with 1 satellite each, or 6.25% of the total 16 satellites.

<img src="images/7 ss.png?raw=true" width="350"/>

### Examining mass

Looking specifically at the satellites, I wrote a SQL inquiry to give me the satellite with the highest mass.

<img src="images/carbon 1 ss.png?raw=true" width="400"/>

The results show that Ganymede, a satellite of Jupiter, has a mass of 148.2 kilograms.

<img src="images/1 ss.png?raw=true" width="350"/>

Following that, I wanted to look at the satellite with the lowest mass.

<img src="images/carbon 2 ss.png?raw=true" width="400"/>

Tethys, one of Saturn's satellites, has a mass of 0.6173 kilograms.

<img src="images/2 ss.png?raw=true" width="350"/>

Next, I wrote an inquiry to show me the average mass of satellites.

<img src="images/carbon 3 ss.png?raw=true" width="400"/>

The average mass is 39.9509 kilograms, which means that 10 satellites are lower than the average, leaving only 6 that are higher.

<img src="images/3 ss.png?raw=true" width="350"/>

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
<br>
Using SQL, I created two CASE inquiries that categorized the satellites by this classification.

The first inquiry classified each satellite into its prospective size category.

<img src="images/carbon 13 ss.png?raw=true" width="400"/>

<img src="images/13 ss.png?raw=true" width="350"/>

The next inquiry looked at the number of planets and satellites that fell into each category.

<img src="images/carbon 12 ss.png?raw=true" width="400"/>

Mid-Earth had the most  classifications with 10 planets and satellites, followed closely by Hyper-Jupiter at 7 and Sub-Jupiter at 6. Super-Earth has 4 planest and satellites, midplanet has 3, and Sub-Earth has 2. Mid-Jupiter and Super-Jupiter both have 1 planet and satellite each, putting them at the bottom of the list.

<img src="images/12 ss.png?raw=true" width="350"/>

### Key insights into planetary satellites

<ul>
  <li>Saturn has the most satellites, possessing <strong>5 satellites out of the 16 recorded</strong>.
  <li><strong>Ganymede</strong>, a satellite of Jupiter, has the <strong>highest mass of 148.2 kilograms</strong>. The satellite with the lowest mass is <strong>Tethys</strong>, one of Saturn's satellites, with <strong>0.6173 kilograms</strong>.</li>
  <li>The <strong>average mass</strong> is <strong>39.9509 kilograms</strong>. This means that <strong>10 satellites</strong> are lower than the average and <strong>6</strong> are higher.</li>
  <li>Planetary mass classification of <strong>Mid-Earth</strong> has <strong>10 planets and satellites</strong>, followed by Hyper-Jupiter with 7 and Sub-Jupiter with 6.</li>
</ul>

To reiterate, Saturn has the most satellites, including the satellite with the lowest mass. The satellite with the highest mass belongs to Jupiter. That satellite is 1 of 6 that is higher than the average satellite mass, leaving 10 that fall below it. 

In addition, using the planetary mass classification system, Mid-Earth has 10 planets and satellites that fall within its range of 0.5 and 2.

Thanks for reading! If you have any questions, please email me at the email below. Also, I am looking for a <strong>full-time remote job as a data analyst</strong>, so if you have any recommendations, please message me on [LinkedIn](https://www.linkedin.com/in/xaviertquinn/) or email me at xaviertquinn@gmail.com. Any information would be very helpful!

---

### [Next project](/)
