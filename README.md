
# Hotel Booking Data Analysis Project 🔥🍁

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/Hotel_Booking_Data_Analysis)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/Hotel_Booking_Data_Analysis)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/Hotel_Booking_Data_Analysis.svg)](https://GitHub.com/Lokesh-Attarde/Hotel_Booking_Data_Analysis/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

![image](https://user-images.githubusercontent.com/84115928/140745716-6591df44-5f14-47e4-a557-6959f9591fd3.jpg)

# 📝Problem Statement
Analysis of the following is required by the Sales Team of Hotel Bookings:
- Analyze What exactly the Home Country of a Guests, What exactly Price distribution of of Room Types per Night.
- Furthermore, Analyze trend of the Room Price, What exactly the Preference of a Guests?, Analyze Months which are having Highest Cancellations.

And so many more!!


Analysis of the following is required by the Sales Team of Hotel Bookings:

    1. Analyze from which Country most guests come?
    2. Country-wise Guests distribution.
    3. Price of Room Types per Night.
    4. How does the Price per Night vary over a Year?
    5. Distribution of Nights Spent at Hotels by Market Segment and Hotel Type.
    6. Preference of Guests in terms of Meal's.
    7. Relationship between Special Requests and Cancellation.
    8. Which are the Most busiest Months throughout a Year.
    9. How long do People Stay at the Hotels?
    10. Price per Night w.r.t. Market Segment and Room Type.
    11. Distribution w.r.t. Cancellation of Bookings.
    12. Which Month have the Highest Number of Cancellations?

And many more!!

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Hotel Booking Dataset](https://github.com/Lokesh-Attarde/Hotel_Booking_Data_Analysis/blob/305582b840d1dccedb983e1c9afaf66e42946588/hotel_bookings.csv)

# 📚 Data Analysis
In the datasets, we are provided with 32 columns(Features) of data.

* **hotel** : Hotel (H1 = Resort Hotel or H2 = City Hotel)
* **is_canceled** : Value indicating if the booking was canceled (1) or not (0).
* **arrival_date_year** : Year of arrival date.
* **arrival_date_month** : Month of arrival date.
* **stays_in_weekend_nights** : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
* **stays_in_week_nights** : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
* **adults** : Number of adults.
* **children** : Number of children.
* **babies** : Number of babies.
* **meal** Type of Meal booked. Categories are presented in standard hospitality meal packages.
* **country** : Country of Origin. Countries are represented in the ISO 3155–3:2013 format.
* **market_segment** : Market segment designation. In categories, the term "TA" means "Travel Agents" and "TO" means "Tour Operators".
* **reserved_room_type** : Code of room type reserved.
* **adr** : Average Daily Rate / Price per night.
* **total_of_special_requests** : Number of special requests made by the customer.

Out of the 32 features given in the datasets, 20 are Continuous and 12 (including the target variable) are Categorical features.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* GitHub is used as version control system.

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/141269995-77714aa7-9b0c-4b11-a94c-e1639a0a743b.png">
</p>

# 🎉 Tasks performed under Time Series Analysis:
* Extract the **"Derived Features"** from the **'Date/Time'** Feature.
* Performed ***Time Series Analysis*** on variety of ***Use Cases*** and Analysed as following:
  * Uber Rides by Weekdays.
  * Uber Rides by and with respect to each and every Months.
  * Month with Max. Rides.
  * Uber Rides in terms of each Day.
  * Total Rides Month-wise.
  * Rush w.r.t. Location and Hour-wise.
  * Popularity of Base by Months.
  * Uber pick-ups by Months in New York City.

# 🌱 Some Exciting Glimpse of the Visuals:
![Final Glimpse 1](https://user-images.githubusercontent.com/84115928/140725706-33748c98-c5b7-4e5c-80e3-b06b9cf1e7de.gif)
![Final Glimpse 2](https://user-images.githubusercontent.com/84115928/140718150-ae634d16-4d21-4250-814e-3a1b246c5996.gif)
![Final Glimpse 3](https://user-images.githubusercontent.com/84115928/140723990-69a9eebd-e130-4ba3-93ec-75ec5857b7f6.gif)
![Final Glimpse 4](https://user-images.githubusercontent.com/84115928/140724037-6c69ef19-e35d-45f9-89af-3f20b9852f54.gif)

For more details, please go through the Jupyter Notebook attached above.

# 💡 Conclusions
* "Rush" is definitely highest on "Thursday" followed by "Friday" and "Wednesday".
* Rush is definitely on Peak during Evening Time when people are logging off from their Work and At the same time, people go out for hang-out or to do a Shopping.
* "September" has the highest Rush or I would say, it has the Maximum Rides.
  Almost in the Couple of Last Days, in Each and Every "Month", we have "Maximum Rides".
* 'Thursday', is on the peak, whereas "Sunday" with respect to our Week-end, is on the root (bottom).
  And, In terms of the Rush, Hour & Location-wise - In the Early Morning at 8 o'Clock of almost each & every day, we've Maximum Number of Rush at this Location (I.e. 40.745) followed by Evening at 4 o'Clock.
* "Base" Number, which is exactly "B02617", gets Popular by Month.
* Almost in Each and Every Day, mostly in the "Evening Time", we have a "Rush" whereas on "Mid-Night", we don't have any kind of "Rush".
* Most of the 'Rush' is there on "Weekdays" rather than the "Week-ends".
  We have Majority of Rides are in "September", it might be because of Autumn Season, people go for excursions to enjoy the natural beauty.
* "Mid-Town Manhattan" is clearly a 'Huge Bright Spot', followed by basically "Upper Manhattan" and "Heights of Brooklyn".
* In this, "6th" Month, we have a Higher Number of Pick-up's followed by "May" and "April".
  We can also say that, The "Number of Uber Pick-up's" has been Gradually Increases throughout the 1st Half of 2015 in "New York".
* After the "Morning Rush", the Number of Uber Pick-up's doesn't decline much throughout the rest of the Morning and early "Afternoon" as well.
  And There is significantly More Demand of Uber Cabs in the "Evening".
* Base Number "B02764" is a Pioneer/Prominent. It has a Maximum Number of 'Active Vehicles' as well as it has a Maximum Number of 'Trips' as well.
* Base Number 'B02598' and 'B02682' are definitely Performed better in terms of Demands and Supply.
  Whereas Base 'B02512', it doesn't have that much Good Attention comparing to All other 'Base Number'.

And so many more!!

# 🎉 Help Me Improve
Hello Mr. Reader, if you find any bug or anything else that could add more value in this project then please consider raising it to me I will address them asap.
  
# 📫 Feedback
If you have any feedback, please reach out to me via [LinkedIn](https://www.linkedin.com/in/lokesh-attarde-145086141/)
