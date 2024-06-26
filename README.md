# MOMA_Artwork_Exploration
Creating visualizations to help simplify and understand data from the Museum of Modern Art

> **This Project**


This is my first project using PowerBI. I thought it'd be interesting to create a dashboard that would help me understand the history behind much of the artwork in the Museum of Modern Art. I've created dashboards in Tableau but I wanted to explore Microsoft's PowerBI as it is becoming more popular. I added columns using DAX which I will discuss more in the data transformation section.

> **Data Transformation**


Unfortunately, the "date" column in the dataset had a myriad of differently formatted values. Some read "1971", and other read "published in 1955". I had to add a column called "year" that extracted the specific year from the date column. Once that was complete, I created another column called "era" that stated which era the artwork was made in. (You'll see why later).

> **Dashboard**


Artwork Through the Decades:
For this visualization, I wanted to show the amount of artwork created in each decade. I figured creating a bar chart would do the job. The bar chart I made also has a legend to show which era the artwork was created in. This visualization gives an insight on the type of art in the MOMA and when they were made. As expected, most were from the Modern Era, but there are also quite a few from other eras.

Peaks per Nationality:
After understanding how the data is spread through the decades, I was interested in finding out more about _where_ they originated. The line graph I created shows the spread of each nation's artwork over time. We can see all of the individual peaks in each of the lines.

Department Acquisition Date:
I was curious about the development of the MOMA. This visualization allows us to see when each department began to get more popular as the museum started acquiring more art. By filtering through specific departments, we can see where the growth occurs. As expected, we can see that Media and Performance along with Film became popular in the early 2000s. Meanwhile, Architecture had peaks in the 40s, 70s, and early 2000s.

> **Conclusion**


Don't get me wrong, the findings were very interesting. However, my biggest takeaway from this project is that I got to learn a lot about PowerBI. I was able to learn how to create calculated fields, add columns for data transformation, and navigate my way through the visualization creation tools. Although it has a lot of similarities to Tableau, it forced me to leave my comfort zone and explore this new tool. I hope you enjoyed going through this PowerBI journey with me!
