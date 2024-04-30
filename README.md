# Hotel Booking Analysis Dashboard
## Overview
This PowerBI visualization project aims to provide insights into hotel booking trends and patterns using a sample hotel booking dataset. The dataset contains information about bookings made by guests, including reservation details, guest demographics, and booking trends over time.
## Features

- Interactive visualizations showcasing various aspects of hotel bookings.
- Insights into booking trends by different demographics.
- Comparison of booking patterns based on room types.
- Comparison of booking patterns between different hotel types.
- Exploration of seasonal booking trends and their impact on occupancy rates.
- Analysing cancellation rates based on waiting time.
## Dataset

The dataset used for this visualization project is added as a CSV file along with the project. Some the key attributes under consideration are:
<li>is_canceled:Dependent variable which indicates whether the booking was cancelled(1) or not(0).</li>
<li>hotel: Type of Hotel (Categorical).</li>
<li>lead_time: Number of days between booking date and arrival date.(Numeric).</li>
<li>arrival_date_year: The year of Arrival date-2015,2016,2017 (Numeric).</li>
<li>arrival_date_month:  Month of  Arrival date.(Categorical).</li>
<li>reserved_room_type:  The Type of Room reserved.(Marked by letters)</li>
<li>country: Country of customer.</li>
<li>market_segment: Market segment designation. In categories, the term "TA" means "Travel Agents" and "TO" means "Tour Operators“.</li>
<li>distribution_channel: Booking distribution channel. The term "TA" means "Travel Agents" and "TO" means "Tour Operators“.</li>
<li>is_repeated_guest: Value indicating if the booking name was from a repeated guest (1) or not (0).</li>
<li>days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer.</li>
<li>customer_type: Type of booking.</li>
<li>adr:  Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights.</li>

## Data Cleaning
- <b>Dropped Unnecessary Columns</b>: Removed columns that do not influence the target variable significantly and those containing personal customer information such as name, credit card, and phone number.
  
- <b>Changed Data Types</b>: Modified the datatype of the 'ADR' variable from decimal to a whole number to improve data interpretability and visualization suitability.
  
- <b>Deleted Outliers</b>: Removed unidentified categories from the columns 'Distribution Channel' and 'Market Segment'.

- <b>Grouped Variables</b>: Calculated the average ADR for both resort hotel and city hotel, as well as monthly average ADR to track season trends. Additionally, months were grouped into seasons for more influential season trend tracking.

- <b>Added New Columns</b>: Introduced new categorical columns such as lead time categories, month numbers for chronological sorting, assignment to waiting list, and ADR categorical based on specified criteria.

- <b>Data Cleaning Tools</b>: Utilized Power Query and Excel for data cleaning and transformation tasks.

## Installation

To run this PowerBI visualization project, follow these steps:

1. Download the repository to your local machine.
2. Open the .pbix file in PowerBI Desktop.
3. If prompted, provide access to the dataset file.
4. Explore the visualizations and insights using PowerBI.




