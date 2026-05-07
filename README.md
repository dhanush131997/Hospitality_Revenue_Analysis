Hotel_Hospitality_Domain_Revenue_Analysis

🔍 Delighted to share my Power BI Project. The Project belongs to Hospitality Domain and deals with the challenges faced by Atliq Hotel Chains which is a Dominant player in Hotel Hospitality Domain and how they can be solved by undertaking data driven decisions. 
I would like to thank codebasics team for providing Raw Data and resources for the same.

📊 𝗞𝗲𝘆 𝗠𝗲𝘁𝗿𝗶𝗰𝘀 for 𝗛𝗼𝘁𝗲𝗹 𝗛𝗼𝘀𝗽𝗶𝘁𝗮𝗹𝗶𝘁𝘆 𝗗𝗼𝗺𝗮𝗶𝗻:-
💰 𝗥𝗲𝘃𝗲𝗻𝘂𝗲: This Kpi helps to monitor the revenue generated and track them across cities, weeks, room class.

📅 𝗔𝗗𝗥: Average Daily Rate is a measure which provides the daily rate of properties depending upon dynamic pricing.

🏠 𝗢𝗰𝗰𝘂𝗽𝗮𝗻𝗰𝘆 %: Gives an understanding of the successful bookings across properties within hotel chain.

✅ 𝗥𝗲𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻 %: Provides information for Actual Successful checkouts when compared to cancellation % or no show %.

📉 𝗥𝗲𝘃𝗣𝗔𝗥:Provides Revenue Per average Room across all properties.

🏘️ 𝗗𝗦𝗥𝗡:Daily Sellable room nights monitors total rooms sold on daily basis.

🏘️ 𝗗𝗕𝗥𝗡:Daily booked room nights monitors total rooms booked on daily basis.

🏘️ 𝗗𝗨𝗥𝗡:Daily utilized room nights monitors total rooms utilized on daily basis.

🛎️ 𝗕𝗼𝗼𝗸𝗶𝗻𝗴 𝗣𝗹𝗮𝘁𝗳𝗼𝗿𝗺: Various Platforms available for bookings and how they contribute to the revenue of the hotel chain.

🌆 𝗖𝗶𝘁𝘆: The locations across which the properties are present.

🚪 𝗥𝗼𝗼𝗺 𝗖𝗹𝗮𝘀𝘀: Analyze data and filter them according to room id and room class.

❌ 𝗖𝗮𝗻𝗰𝗲𝗹𝗹𝗮𝘁𝗶𝗼𝗻 %: Provides insights on the number of bookings cancelled.

🌟 𝗔𝘃𝗴 𝗥𝗮𝘁𝗶𝗻𝗴 %: Provides insights on the average ratings the properties have recieved.


💡 𝗞𝗲𝘆 𝗟𝗲𝗮𝗿𝗻𝗶𝗻𝗴𝘀:-
✨ We can see that 𝗔𝗗𝗥 remains consistent throughout 𝘄𝗲𝗲𝗸𝗱𝗮𝘆 and 𝘄𝗲𝗲𝗸𝗲𝗻𝗱𝘀 hence we can conclude there is no dynamic pricing present. Management can initiate the concept of Dynamic Pricing gaining Maximum Realization %.

✨ One can observe by dashboard that 𝗢𝗰𝗰𝘂𝗽𝗮𝗻𝗰𝘆 % stands above 50% throughout all weeks hence we can conclude that Hotel Chains are gaining good amount of customers.

✨ Overall 𝗮𝘃𝗲𝗿𝗮𝗴𝗲 𝗿𝗮𝘁𝗶𝗻𝗴 is found to be 3.62 which is satisfactory, but focus should be there on increasing it.

✨ We can see a direct relationship between 𝗔𝘃𝗴 𝗥𝗮𝘁𝗶𝗻𝗴 and 𝗢𝗰𝗰𝘂𝗽𝗮𝗻𝗰𝘆 %, hotel chains which are having less Occ% are providing less ratings hence focus should be on them.

✨ 𝗠𝗮𝗸𝗲𝗺𝘆𝗧𝗿𝗶𝗽 and others platform are generating more revenue than other booking platforms.



🧭 𝗠𝗲𝘁𝗵𝗼𝗱𝘀 :-
🌐 Data Modelling

🌐 DAX language

🌐 Power Query

🌐 Creating Calculated Columns and Measures

🌐 DAX studio for optimizing performance.

🌐 Microsoft Excel Power Pivot for data verification purpose.

Total 5 CSV files Data has been imported into our Project:-

dim_date
dim_hotels
dim_rooms
fact_aggregated_bookings
fact_bookings

Column Description for dim_date:

1) date: This column represents the dates present in May, June and July.
2) mmm yy: This column represents the date in the format of mmm yy (monthname year).
3) week no: This column represents the unique week number for that particular date.
4) day_type: This column represents whether the given day is Weekend or Weekeday.

Column Description for dim_hotels:

1) property_id: This column represents the Unique ID for each of the hotels.
2) property_name: This column represents the name of each hotel.
3) category: This column determines which class[Luxury, Business] a particular hotel/property belongs to.
4) city: This column represents where the particular hotel/property resides in.

Column Description for dim_rooms:

1) room_id: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
2) room_class: This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.

Column Description for fact_aggregated_bookings:

1) property_id: This column represents the Unique ID for each of the hotels.
2) check_in_date: This column represents all the check_in_dates of the customers.
3) room_category: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
4) successful_bookings: This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.
5) capacity: This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.

Column Description for fact_bookings:

1) booking_id: This column represents the Unique Booking ID for each customer when they booked their rooms.
2) property_id: This column represents the Unique ID for each of the hotels
3) booking_date: This column represents the date on which the customer booked their rooms.
4) check_in_date: This column represents the date on which the customer check-in(entered) at the hotel.
5) check_out_date: This column represents the date on which the customer check-out(left) of the hotel.
6) no_guests: This column represents the number of guests who stayed in a particular room in that hotel.
7) room_category: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
8) booking_platform: This column represents in which way the customer booked his room.
9) ratings_given: This column represents the ratings given by the customer for hotel services.
10) booking_status: This column represents whether the customer cancelled his booking[Cancelled], successfully stayed in the hotel[Checked Out] or 1 booked his room but not stayed in the hotel[No show].
11) revenue_generated: This column represents the amount of money generated by the hotel from a particular customer.
12) revenue_realized: This column represents the final amount of money that goes to the hotel based on booking status. If the booking status is cancelled, then 40% of the revenue generated is deducted and the remaining is refunded to the customer. If the booking status is Checked Out/No show, then full revenue generated will goes to hotels.
