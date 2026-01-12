Project Overview:-
This project consists of a set of SQL queries designed to analyze a digital music store's database (based on the popular Chinook Database schema). The goal is to derive actionable insights for business growth, marketing strategies, and operational efficiency. The analysis answers critical business questions regarding employee hierarchy, customer purchasing behavior, music genre popularity, and artist performance.

Business Problems Solved:-
1. Employee Analysis
Objective: Identify the senior-most employee within the organizational hierarchy.

Approach: Sorted employees by job title levels in descending order.

2. Global Sales Distribution
Objective: Determine which countries generate the highest number of invoices to identify top-performing markets.

Approach: Grouped invoice counts by billing country.

3. High-Value Transactions
Objective: Identify the top 3 highest invoice totals to understand peak transaction values.

Approach: Sorted global invoice totals in descending order.

4. Promotional Event Planning (City Analysis)
Objective: Determine the best city to host a promotional Music Festival based on revenue.

Approach: Aggregated total invoice sums by city to find the location with the highest profit.

5. Customer Lifetime Value (CLV)
Objective: Identify the "Best Customer" to offer rewards or loyalty status.

Approach: Calculated the total spending per customer by joining Customer and Invoice tables.

6. Marketing Campaign: Rock Music Listeners
Objective: Create an email list of customers who listen to Rock music for a targeted marketing campaign.

Approach:

Method 1: Used nested subqueries to filter by Genre.

Method 2: Used multiple Joins to link Customers to Genres directly.

Output: An alphabetical list of emails and names.

7. Artist Inventory Analysis
Objective: Identify the top 10 Rock bands based on the number of tracks in the dataset to manage inventory.

Approach: Joined Artist, Album, Track, and Genre tables to count tracks per artist filtered by the 'Rock' genre.

8. Track Length Optimization
Objective: Analyze song duration trends by identifying tracks longer than the average song length.

Approach: Used a subquery to calculate the global average duration and filtered tracks exceeding that value.
