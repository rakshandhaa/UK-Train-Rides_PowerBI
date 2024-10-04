# Travel Trends for Rail Managers - UK Train Rides 

## Project Overview: 
This project presents a mock dataset of train ticket information for the National Rail service in the UK, covering the period from January to April 2024. 
The dataset includes comprehensive details about each journey, including:
* Type of Ticket: Information on various ticket categories such as standard, first class, and off-peak.
* Date & Time: The scheduled departure and arrival times for each journey.
* Departure & Arrival Stations: Details of the stations at which the journey begins and ends.
* Ticket Price: The price for each ticket, allowing for financial analysis and insights.
* Additional Attributes: Any other relevant data that enriches the dataset, such as travel class, distance, and journey duration.

## Project objectives:

* Popular Routes: Identify the most traveled routes.
* Peak Travel Times: Determine high-traffic periods.
* Revenue Analysis: Examine revenue variations by ticket types and classes.
* On-Time Performance: Evaluate punctuality and factors contributing to delays.

## Data Preparation: 
When I initially imported the dataset into Power BI, I focused on enhancing its quality and consistency through the Power Query Editor. Here’s a summary of the key steps I took:

*Data Integrity Check:* I began with a comprehensive assessment of each column to identify and correct any discrepancies in data types and values.

*Standardization of Delay Reasons:*
* Consolidated terms in the "Reason for Delay" column for uniformity.
* Replaced both "Staffing" and "Staff Shortage" with "Staff Shortage"
* Converted "Weather Conditions" and "Weather" into "Weather Conditions"
* Unified variations of "Signal failure" and "Signal Failure" to "Signal Failure."

*Introduction of a Route Column:* I created a new column called "Route" by merging the "Departure Station" and "Arrival Station" columns.
This enhancement was achieved using the merge function in the Power Query Editor, allowing for a clearer understanding of specific travel routes.

*Additional Adjustments:* I implemented several minor changes throughout the dataset to improve its overall consistency and quality.

These steps ensured that the dataset was clean and ready for insightful analysis and visualization in the dashboard.

## Dashboard Overview : 
An interactive dashboard has been developed to provide valuable metrics for various ride types. 
The KPIs dynamically adjust according to the selected category—whether it’s All Rides, On-Time Rides, Delayed Rides, or Cancelled Rides. 
This feature enables users to focus on the most relevant metrics for each specific category.

💡𝗞𝗲𝘆 𝗠𝗲𝘁𝗿𝗶𝗰𝘀 𝗖𝗼𝘃𝗲𝗿𝗲𝗱:
* Gross/Net Tickets & Revenue
* Refund Requests & Amounts
* On-Time, Delayed, and Cancelled Rides Revenue

💡 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗛𝗶𝗴𝗵𝗹𝗶𝗴𝗵𝘁𝘀:
1. 𝗣𝗼𝗽𝘂𝗹𝗮𝗿 𝗥𝗼𝘂𝘁𝗲𝘀:
* Manchester Piccadilly to Liverpool Lime Street is the most popular route, with 4,628 rides and £16,976 in net revenue.
* London Kings Cross to York generates the highest revenue: £179,498 from 3,922 rides.
2️ 𝗣𝗲𝗮𝗸 𝗧𝗿𝗮𝘃𝗲𝗹 𝗧𝗶𝗺𝗲𝘀:
* Morning: 6 AM, 7 AM, 8 AM
* Evening: 4 PM, 5 PM, 6 PM
3️ 𝗥𝗲𝘃𝗲𝗻𝘂𝗲 𝗕𝗿𝗲𝗮𝗸𝗱𝗼𝘄𝗻:
* Users can observe revenue by purchase type. Online revenue amounts to £383k, while station revenue accounts for £359k.
* By ticket class, standard class generates £593k, and first class contributes £149k.
* By payment method, credit card bookings lead with £470k. Users can also analyze revenue from contactless and debit card transactions.
* Revenue by ticket type shows Advance tickets generated £309,274, Off Peak tickets generated £223,338, and Anytime tickets contributed £209,309.
4️ 𝗢𝗻 𝗧𝗶𝗺𝗲 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲:
* 86.82% of rides are on time, generating £569,651 in revenue.
* Delayed and Cancelled rides, often due to weather and signal failures, make up 13.18%.
  
📍 𝗗𝗲𝗲𝗽 𝗗𝗶𝘃𝗲𝘀 𝗼𝗻 𝗗𝗲𝗹𝗮𝘆𝘀 & 𝗖𝗮𝗻𝗰𝗲𝗹𝗹𝗮𝘁𝗶𝗼𝗻𝘀:
* Delayed Rides: Liverpool Lime Street to London Euston has the highest number of delayed rides (780).
* Cancelled Rides: Manchester Piccadilly to Liverpool Lime Street sees the most cancellations (290), with staff shortages being a key factor.

This dashboard’s dynamic KPIs allow users to tailor their focus and drive better decisions around UK train operations.
🎯 𝗧𝗼𝗼𝗹𝘀 𝗨𝘀𝗲𝗱:
• Power BI
• Excel

This dashboard’s dynamic KPIs allow users to tailor their focus and drive better decisions around UK train operations.
