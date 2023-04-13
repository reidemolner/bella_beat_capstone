![download](https://user-images.githubusercontent.com/125325076/230917985-81e5bd8f-8b06-41f9-9a5a-f9295a125cdb.jpg)

**Case Study: How Can a Wellness Technology Company Play It Smart?**

For this case study I am following the 6 steps of the data analysis process: **Ask, Prepare, Process, Analyze, Share and Act.**


**Background:** Bellabeat is a tech-driven female wellness company that specializes in the manufacturing of health focused smart products including Bellabeat app, leaf, spring, and the bellabeat subscription membership. Since its founding in 2013 the company has steadily grown into a world wide entity in the fitness tracking industry for women, but they have the potential to become an even larger player in the global market. Bellabeat has invested the majority of their resources into digital marketing, including Google and social media. 

**1. Ask** :turtle:

**Business Task**

Urška Sršen, co-founder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. I have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. I’ve chosen to focus on the Bellabeat app because it is the foundation of the company, and is the common thread woven throughout their products. 

**Stakeholders:**

Urška Sršen: Bellabeat’s co-founder and Chief Creative Officer

Sando Mur: Mathematician, Bellabeat’s co-founder and key member of the Bellabeat executive team

Bellabeat marketing analytics team: A team of data analysts guiding Bellabeat’s marketing strategy. 

***2. Prepare*** :mage:

The data is stored and publicly available at https://www.kaggle.com/datasets/arashnic/fitbit

The dataset has 30 participant’s FitBit Fitness Tracker Data, comprising 18 CSV files.

**ROCCC: Is it good or bad data?**

**Reliability:** The data is from 30 FitBit users that consented to submit their personal tracker data. Upon further review there are 33 unique IDs for the daily data sets, 24 for sleep data, and only 8 for the weight log data. The 33 sources of data is enough to meet the generally accepted threshold of 30 participants, however a sample size this small will not provide a highly informed analysis. 

**Original:** Data collected from 3rd Party Amazon Mechanical Turk, data is not original.

**Comprehensive:** The data includes the date, total steps taken, total distance covered, whether the time spent was sedentary, lightly active, fairly active, or very active, and how many calories were burned. There is also data covering sleep metrics, and a weight log. However, we don’t know anything else about the participants.

**Current:** The data is from April 2016 to May 2016. Although the data is 7 years old, it should represent a general theme amongst FitBit wearers that hasn’t changed with time. 

**Cited:** Although the data is cited it is collected from unknown sources which may be unreliable.

***3 & 4. Process, & Analyze*** :giraffe: :muscle:

When I initially began the project I was exclusively using SQL and Excel in order to clean and organize the data. After some struggle it became obvious that I would need to go another route in order to best visualize the data. Although the Google Data Analyst Certification Course uses R, I found it extremely difficult to use, so I learned Python instead and used that to analyze the data.

**Below is a link to the Python code used.** 

+ https://github.com/reidemolner/bella_beat_capstone/blob/main/bella_beat_final-Copy1.ipynb


***5. Share*** :telephone:


![download](https://user-images.githubusercontent.com/125325076/231813661-39dac2a6-8c9c-4045-b75a-9ddbd0aba27f.png)

+ As you can see the vast majority of time spent by users was sedentary, making up 81.3%.

+ Lightly active minutes makes up the second highest at 15.8%.

+ Fairly active and Very active make up 1.1% and 1.7% respectively, combining for under 3% of total time spent.

+ This more than likely means that we are dealing with a group of people that are working most of their waking time and are unable to move around while at work, walking a minimal amount at work or around the house, and leaving very little time for meaningful exercise. For a group of people that are focusing on their health by using a fitness tracking app, this is a sign that most aren't able to put their fitness needs above or before their work.


![download](https://user-images.githubusercontent.com/125325076/231813937-ad9e1089-a217-4579-b26c-e429bcfb4ad4.png)

+ This graph shows how frequently our participants logged into their app, sorted by the day of the week.

+ Participants generally logged on the same amount throughout the week with the exception of increased turnout during the middle of the work week from Tuesday to Thursday, with Tuesday being the highest. One theory could be that people are trying to provide themselves with motivation to get through the week by practicing good habit implementation, however the behavior drops off as the weekend gets closer.  


![download](https://user-images.githubusercontent.com/125325076/231813738-74aba1ab-ff11-41c0-811c-636092fb9c74.png)

+ This graph confirms our preconceived ideas that the more steps someone takes, the further distance they will travel. There could be some variation due to different participants stride length, however the data set doesn't provide that information.




![download](https://user-images.githubusercontent.com/125325076/231813862-88661173-0393-4552-b756-f5f709b73f60.png)

+ There is a positive correlation between calories burned, and steps taken.

+ The majority of users averaged between 0 - 15,000 steps, and burned 1,000 to 3,000 calories.

+ A significant number of people reported 0 steps taken which is more than likely inaccurate.

+ The most notable outlier of the group is for someone that went over 35,000 steps in a single day, while burning less than 3,000 calories.



![download](https://user-images.githubusercontent.com/125325076/231813899-213c98ff-db4a-4e80-a6f9-4b93a69c1bdc.png)

+ There is a positive correlation between hours logged and calories burned. It is not as significant as the previous two graphs, but it does signifiy that there is evidence that generally speaking the more time you spend engaged with a fitness app, the more calories you will burn as a result. 

***6. Act*** :1st_place_medal:

**Insights and trends analyzed**

+ Peole tend to track more data during the middle of the work week from Tuesday through Thursday. This could be due to forgetting over the weekend, or simply wanting to "let loose" after focusing on their health more during the weekdays. Monday is also slightly lower which may suggest that people are just doing their best getting back to work for the week.

**Our Participants spent 81.3% of their time sedentary which is quadruple more than the other 3 combined.**

There is a relatively strong positive correlation between engagement with the fitness app and calories burned.  

**How does this apply to Bellabeat customers?**

+ Although fitbit data was being dissected, the insights and trends analyzed are directly applicable towards the bellabeat app.

**How can this influence Bellabeat's marketing strategy going forward?**

+ Bellabeat could try and implement some sort of buzzing or sound notification that reminds the wearer of their product to stand up and move around. They would also benefit from having the app be more interactive with a user if they are not logging in to track their data. If possible, Bellabeat should track patterns of behavior for each individual user and show them a graphic of their behavior. For example if a user has not been engaging with their app on the weekends, they could receive a notification with a visual that shows how they are not putting in the same amount of effort as they are during the week. There could also be some sort of incentive program built in for users that consistently engage with their app on a regular basis, perhaps Bellabeat could provide discounts on some of their other apparel and gear to show that they appreciate their diehard customers.

