# Atliq-Hospitality-Domain-Analysis
##### AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights. Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

##### As a Power BI Analyst
##### 1.I have created the metrics.
##### 2.Created a dashboard according to the mock-up provided by stakeholders.
##### 3.Created relevant insights.

Client: AtliQ Hospitality
Objective: Enable the CEO and leadership team to take data-driven strategic decisions by visualizing critical metrics across cities and hotels.

This project involved designing an interactive dashboard using hotel booking data from May 2022 to July 2022 to uncover insights related to:

- Revenue generation sources
- Occupancy and cancellation patterns
- Platform performance
- Customer ratings and booking behavior

🎯 Business Objectives
- Identify key revenue sources across hotels and platforms
- Clean and model data for dashboard integration
- Develop an interactive KPI dashboard using Power BI
- Provide high-level and granular insights with slicers and filters

🧰 Tools & Technologies
- Power BI (Data Visualization)
- Power Query (Data Cleaning)
- Power Pivot (Data Modelling)
- Relational Model with:
- 3 Dimension Tables: Date, Hotel, Room
- 2 Fact Tables: Bookings, Aggregated Bookings

### 🧼 Data Cleaning & KPIs Calculated
- Custom measures created:
- Revenue = SUM(revenue_realized)
- Total Bookings = COUNT(booking_id)
- Avg Rating = AVERAGE(customer_rating)
- Total Capacity = SUM(capacity)
- Successful Bookings = SUM(successful_bookings)
- Occupancy Rate = Successful Bookings / Total Capacity
- Cancelled Bookings = COUNT(booking_id WHERE status = 'cancelled')

- Cancellation Rate = Cancelled Bookings / Total Bookings
- Avg Stay Duration = AVERAGE(days_stayed_per_booking)

📈 Business Insights
- Mumbai recorded the highest revenue; Delhi the lowest.
- Occupancy is consistently higher on weekends.
- 75% of bookings result in revenue (checked out or no-show).
- Cancellation analysis is essential to minimize lost revenue.
- Average customer rating: Between 3.4–3.8
- Average stay duration: 2.4 days
- Delhi shows 60%+ occupancy but low revenue – an opportunity to investigate and optimize pricing or upselling.

🧠 Key Takeaways
- Dashboard enables both high-level overview and drill-down into city- and hotel-level metrics.
- Strategic focus recommended on Delhi, weekend optimization, and cancellation management.
- Real-time dashboard can evolve into a revenue intelligence system for the client.

🏁 Conclusion
This dashboard equips AtliQ Hospitality with a powerful tool to track, measure, and optimize performance across properties. It is an ideal use-case of how data visualization can drive smarter hospitality decisions.


