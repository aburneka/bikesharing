# Pedal Power
## Project Overview 

This proposal uses New York City bikesahring data from Citi Bike during the month of Augusut, 2019. We hope to use this data to show the value of a bikesharing company, such as CitiBike, for the Des Moines, Iowa region. Using Tableau we have created an aesthetically pleasing presentation to show the sixe of the market, understand peak rider times and areas, repair & maintenance costs as well as taking a look at demographics such as gender or age make a difference in the bikeshare market. 

## Resources

Data: 201908-citibike-tripdata-modified.csv from the [Citi Bike System Data Page](https://www.citibikenyc.com/system-data)

Software: Tableau Public, Jupyter Notebook, Python 3.7.6, VS Code

Find the Visualizations in Tableau [here](https://public.tableau.com/views/Bikesharing_16242475431290/DesMoinesBikesharing?:language=en-US&:display_count=n&:origin=viz_share_link)

## Analysis 

### NYC Market Snapshot 

There were 2,344,224 rides taken in August of 2019. 

The majority of riders appear to start rides in the Manhattan borough as seen in image 1: 

<img width="797" alt="Top  Starting Locations" src="https://user-images.githubusercontent.com/79999761/122859689-40acdb00-d2d1-11eb-8532-cd0df96a9f42.png">
image 1: Top Starting Location



The majority of clients taking rides in August (81%) have a subscription service, which is an annual pass, while 19% of clients used a 24-hour or 3 day pass (see images 3 and 4). 

<img width="462" alt="Number of Subscribers" src="https://user-images.githubusercontent.com/79999761/122859703-46a2bc00-d2d1-11eb-9569-1c3cbbba2715.png">
image 2: Number of Subscribers

<img width="470" alt="Number of Customers" src="https://user-images.githubusercontent.com/79999761/122859717-4d313380-d2d1-11eb-85e5-1dcdc265f0f2.png">
image 3: Number of Customers


## When and for how long are people riding bikes? 

Most trips were around 15 minutes long as seen in image 4. 

<img width="1034" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/79999761/122859875-91243880-d2d1-11eb-803a-63d05f6b86f7.png">
image 4: Checkout Times for Users 



The peak hours for August were from 8-10 AM and 5-7 PM EST: 

<img width="1035" alt="August Peek Hours" src="https://user-images.githubusercontent.com/79999761/122859884-941f2900-d2d1-11eb-8ec6-e416df092a55.png">
image 5: August 2019 Peak Hours 


### Demographics 

The majority of those using CitiBikes are doing soMonday - Friday in the mornings, from 8-10 AM, and early evening, 5-7 PM EST. Most clients checking out the bikes identified as male. 

<img width="333" alt="Gender Breakdown" src="https://user-images.githubusercontent.com/79999761/122859815-75b92d80-d2d1-11eb-87d5-0082a59b15c9.png">
image 6: Gender Breakdown 

<img width="364" alt="Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/79999761/122859825-7b167800-d2d1-11eb-9346-979a560543d4.png">
image 7: Trips by Gender by Weekday 

<img width="1053" alt="Trips by Gender (Weekday per Hour)" src="https://user-images.githubusercontent.com/79999761/122859832-7ea9ff00-d2d1-11eb-986f-3e577fff7c46.png">
image 8: Trips by Gender (Weekday per Hour) 

<img width="1048" alt="Checko0ut Times by Gender" src="https://user-images.githubusercontent.com/79999761/122859845-85387680-d2d1-11eb-8fb5-256f1e06cebe.png">
image 9: Checkout Times by Gender

Image 10 shows the average trip duration for all users based on their reported year of birth. Users born between 1995-2003 have the highest average trip duration. There is a significant spike in users born after 1998 implying that younger populations in NYC may not own cars and are more likely to use the bikeshare service.

<img width="890" alt="AVG Trip Duration by Birth Year " src="https://user-images.githubusercontent.com/79999761/122976768-9755fb80-d349-11eb-8776-0e0df35dd0ae.png">
image 10: Average Trip Duration by Birth Year


### Conclusion

The bike sharing program in NYC showed success with a large subscriber base indicating that there are likely a lot of people in New York City who are utilizing the bikes for a daily commute. Casual users use the service to move between tourist spots on the weekends. This program would be successful in Des Moines if the working demographic is centralized in a downtown area where people would be using the bikes for their commutes. Additionally, success would rely heavily on the younger male population as they were the largest userbase of the CitiBike NYC program. Also, the program should focus on marketing the program to younger tourists as an alternative means of travel from one attraction to the next as well as females as an option for tourism or as part of their commute.



#### Limitation of Data 

The date only looks at the month of August in one year. It would be beneficial to look at longer time periods to see how successful a bikeshare company would do in a smaller city vs. NYC. What does bike usage look like in the winter months? Is there enough usage during summer months to makeup for slower months? 

There is no pricing information. It is impossible to tell from this data if there is a profit to be made in bikesharing. Also, there is no information on the cost of bike maintenance or details about bike loss. How many bikes are stolen or damaged beyond repair? 

We would want to look at details about Des Moines. What are the demographics like? Do people live in urban areas or suburban areas where they would likely need a car for their commute? What does tourism look like for Des Moines? 

